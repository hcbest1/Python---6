# Python---6

{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyMEqEbdNF+zIiPygWEPxyAj",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/ciellleen/copyright/blob/main/6%EC%9D%BC%EC%B0%A8.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": 1,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "hR0b1_ydOQFe",
        "outputId": "e11af212-9f59-4179-add4-47de54278b9b"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "hello\n",
            "hello\n"
          ]
        }
      ],
      "source": [
        "x = input()\n",
        "print(x)"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "str = input(\"How old are you:\")\n",
        "print(str,'years old')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "HiGxuNTJOsIN",
        "outputId": "dd9e4f8d-c6eb-4b53-fa28-5dd1415fc2c6"
      },
      "execution_count": 2,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "How old are you:21\n",
            "21 years old\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "x = int(input('number ; '))\n",
        "print(x)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "dTgUec5UO5g8",
        "outputId": "9f132f65-f94f-4871-fbd3-6434215d9e8b"
      },
      "execution_count": 6,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "number ; 1234\n",
            "1234\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "x = float(input('number ; '))\n",
        "print(x)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "_G1tJJHSO5jr",
        "outputId": "893f8a1a-7a0d-4bf3-d503-50fbd8ebec02"
      },
      "execution_count": 5,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "number ; 1.234\n",
            "1.234\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "year = input (\"This year: \")\n",
        "print(year)\n",
        "year = eval(year)\n",
        "year+=1\n",
        "print(\"Next year: \", year)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "rsu5xtmjO5mE",
        "outputId": "14e750bc-7cd6-4c04-fe3f-5453add3f9da"
      },
      "execution_count": 7,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "This year: 2024\n",
            "2024\n",
            "Next year:  2025\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "i = 0\n",
        "result = 0\n",
        "while i < 5:\n",
        "  a =  input(\"성적 입력 : \")\n",
        "  result += int(a)\n",
        "  i += 1\n",
        "\n",
        "print(f'평균 : {result / 5}')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "BfStX3jmO5qj",
        "outputId": "25baf7ee-1c9c-45e2-df20-1c4c520f2bfc"
      },
      "execution_count": 11,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "성적 입력 : 12\n",
            "성적 입력 : 34\n",
            "성적 입력 : 56\n",
            "성적 입력 : 78\n",
            "성적 입력 : 90\n",
            "평균 : 54.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "test_list = ['one', 'two', 'three']\n",
        "for i in test_list:\n",
        "  print(i)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "fMhXN-BgO5s0",
        "outputId": "730a2726-892a-4a28-b430-e389bcdb9592"
      },
      "execution_count": 12,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "one\n",
            "two\n",
            "three\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "for i in range(10):\n",
        "  print(i)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "kCzNdOBWO5vj",
        "outputId": "b759b7ca-5e47-4030-8043-5909b17df422"
      },
      "execution_count": 13,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "0\n",
            "1\n",
            "2\n",
            "3\n",
            "4\n",
            "5\n",
            "6\n",
            "7\n",
            "8\n",
            "9\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "result = 0\n",
        "for a in range(1,101):\n",
        "  result += a\n",
        "\n",
        "print(result)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "ZsNWZ4vTP2rr",
        "outputId": "f56d579a-a8e1-4ac9-d26d-a833bc73d1e5"
      },
      "execution_count": 14,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "5050\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "index = 0\n",
        "s = \"BlockDMask\"\n",
        "for a in s :\n",
        "  if a == 'k':\n",
        "    break\n",
        "\n",
        "  index+=1\n",
        "\n",
        "print(index)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "RyKFIs5BQARy",
        "outputId": "67fd641a-0c82-4333-8cf1-edcf05ecd762"
      },
      "execution_count": 15,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "4\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "result = 0\n",
        "for a in range(1,101):\n",
        "  result += a\n",
        "\n",
        "  if result > 100:\n",
        "    print(a)\n",
        "    break"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "-xCTe8XrQAUb",
        "outputId": "95230bb3-ca56-4cff-b8a6-bc8aa54b58fd"
      },
      "execution_count": 16,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "14\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "student = [180, 170, 164, 199, 182, 172, 177]\n",
        "for a in student:\n",
        "  if a>170:\n",
        "    continue\n",
        "  print(a)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Tu7p8PuCQAYa",
        "outputId": "c14a5c44-14f6-4fb4-e20b-2dc4b6b3f31e"
      },
      "execution_count": 17,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "170\n",
            "164\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "result = 0\n",
        "for a in range(1,101):\n",
        "  if a % 2 == 1:\n",
        "    result += a\n",
        "\n",
        "print(result)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "QI_bcX6KQDMC",
        "outputId": "b91de9ba-3ec6-4147-f696-520ef235cd32"
      },
      "execution_count": 18,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "2500\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = ['Alice','Bob','Charlie']\n",
        "\n",
        "for name in a:\n",
        "  print(name)\n",
        "else:\n",
        "  print('!!FINISH!!')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "zXF_RRVMQXbp",
        "outputId": "c6626890-dbb3-43d9-d657-faab99233bde"
      },
      "execution_count": 19,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Alice\n",
            "Bob\n",
            "Charlie\n",
            "!!FINISH!!\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = ['Alice','Bob','Charlie']\n",
        "\n",
        "for name in a:\n",
        "  if name == 'Bob':\n",
        "    print('!!BREAK!!')\n",
        "    break\n",
        "  print(name)\n",
        "else:\n",
        "  print('!!FINISH!!')"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "auaSz1f0QXeJ",
        "outputId": "ba2534a3-ada4-4f31-f726-5ded8c24a823"
      },
      "execution_count": 20,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Alice\n",
            "!!BREAK!!\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "sr = ['father', 'mother', 'brother']\n",
        "cnt = 0\n",
        "for s in sr:\n",
        "  for c in s:\n",
        "    if c == 'r':\n",
        "      cnt += 1\n",
        "\n",
        "print(cnt)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "wdrFTIlFQXgp",
        "outputId": "b8d7c769-343e-416a-b91d-e95d82b277bf"
      },
      "execution_count": 21,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "4\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = []\n",
        "for i in range(10):\n",
        "  a.append(0)\n",
        "\n",
        "print(a)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "DRI8bnwOQXjS",
        "outputId": "652d0356-d93c-40ef-944a-9f6347ad160f"
      },
      "execution_count": 22,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[0, 0, 0, 0, 0, 0, 0, 0, 0, 0]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = []\n",
        "\n",
        "for i in range(3):\n",
        "  line = []\n",
        "  for j in range(2):\n",
        "    line.append(0)\n",
        "  a.append(line)\n",
        "\n",
        "print(a)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "fsDwqUcFQXlw",
        "outputId": "610362ca-1d40-46dd-959e-ef76cc9fb972"
      },
      "execution_count": 23,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[[0, 0], [0, 0], [0, 0]]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(list(range(0,10,3)))"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "3VSwuWIlQ9xJ",
        "outputId": "239ae20b-586f-460c-bcee-6a5e5e063dd4"
      },
      "execution_count": 26,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[0, 3, 6, 9]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(list(range(10,0,-3)))"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "kVgvptkoQ9zo",
        "outputId": "e1a44764-1002-4f62-9459-13bcffc2ec92"
      },
      "execution_count": 25,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[10, 7, 4, 1]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "for i in range(10, 0, -3):\n",
        "  print(i)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "G-80gv4WQ91_",
        "outputId": "7229ff88-9281-4ab5-95ff-dc53a5dea596"
      },
      "execution_count": 24,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "10\n",
            "7\n",
            "4\n",
            "1\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = ['Alice','Bob','Charlie']\n",
        "\n",
        "for name in a:\n",
        "  print(name)\n",
        "\n",
        "for i, name in enumerate(a):\n",
        "  print(i, name)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "CCdkz_qbQXoA",
        "outputId": "d91c5921-53f5-497c-9838-d32788db5106"
      },
      "execution_count": 27,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Alice\n",
            "Bob\n",
            "Charlie\n",
            "0 Alice\n",
            "1 Bob\n",
            "2 Charlie\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "student = [180, 170, 164, 199, 182, 172, 177]\n",
        "for a in student:\n",
        "    if a > 170:\n",
        "        continue  # 키가 170보다 크면 continue\n",
        "    print(a)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "V4ryhLXxTfzi",
        "outputId": "392a9b0d-f6b1-47f1-e0b9-9d4548038140"
      },
      "execution_count": 29,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "170\n",
            "164\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "result = 0\n",
        "for a in range(1,101): #1~100\n",
        "  if a % 2 == 1:\n",
        "    result = result + a\n",
        "print(result)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "0RA8LyaNUExR",
        "outputId": "3a6047b0-de7c-420f-8608-2ba9eee1a0d2"
      },
      "execution_count": 30,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "2500\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        ">>> int('1011', 2)\n",
        "13"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "5Ka0nm0LVxkn",
        "outputId": "0d675f7f-f828-4f6f-a33d-ae586d12578a"
      },
      "execution_count": 31,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "13"
            ]
          },
          "metadata": {},
          "execution_count": 31
        }
      ]
    }
  ]
}
