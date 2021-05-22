### Bài tập

Bạn hãy tạo ra lớp `Student` trong file `Student.cpp` với thông tin giống như sau:

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAANEAAACsCAYAAADlhknwAAAgAElEQVR4Ae2dZ8xURRfHid/94gcSP72JiTHGGGOI0WgMGg0aNZQEUSMWsPdYggUpiooYLASixqixS7CjsUXFCnYRsYMFFUHFjgXLffMb8l/PDnP3ubt77z677Jnkee7de+dOOXP+M2fOnDkzJPPgFHAKtEWBIW197R87BZwCmYPImcAp0CYFHERtEtA/dwo4iJwHnAJtUqAGoiFDhmT+5zRwHsjngTys1YHo7rvvzhYtWuR/TgPnAcMD4ILOJS/U3hDps88+y4vnz50CfUsBcOEg6tvm94qXQQEHURlU9DT6mgIOor5ufq98GRRwEJVBRU+jryngIOrr5vfKl0EBB1EZVPQ0+poCDqK+bn6vfBkUcBCVQcVBTuOOO+4I6xQ77bRT9sEHHwxyafovewdRC23+zz//ZIsXL86OPfbYbLvttquZQ+22227ZjBkzss8//7yFVFv/xEHUOu3K+NJB1CQV//rrr+zyyy+vASdlS7brrrtm7733Xi3lP/74Izv99NOz/fbbL/vuu+9qz8u66TSI7rvvvlD/F198sawq9HQ6DqImm2/58uXZ9ttvH5ho2rRp2U8//RRSYHR65JFHsv/973/hHaABPAR9szmA6Ndff82OPvpoB5HhGweRIUaRW3pfjT7PPfdc3Sd///13dsEFF2R77rlnduGFF2bffPNNdsIJJ9Ti6zuBKW8EYbQiDvEvvvjiWh6Mghg7MtLxjnwWLlyY3XbbbeF3PCeC4a+99tps+PDh4T0AP/PMM7NPP/20luZvv/1WK+Nll12WrVu3LtRhq622yvijPjwjqLyqh679PiI5iGrsVOzm7bffzrbddtvAlIcddlj20UcfZYxCqfD7778HMO28884hPky59957h7nU999/X2PKmPlTIPr333+zO++8M9tyyy1DWszF9t1332ybbbbJDjjggPDMpgOATj755PB8xx13zCZPnpwdfPDB4bcVNy2IGD2PPPLIEEcA4Xr22WeHUfXBBx8MwFUZmAOOGDEie/3111PV75tnDqImmxoR7bzzzqtjNBgaEQcmh6AxqNSDawRSlnpumZ93KRB9++232f777x/yPeKII7IffvghJIMSA2DC7DYdzVt4pvkZIxmKD+JOmTIlY+S0INp6662zm266KQDm559/DmAn7rBhw7KPP/445If2jzR53u8jkNrRQSRKNHEFSPfee2+2zz77BGaCoezfQQcdlL3//vu1FAWWdkBEbw+Tkw/p2XDVVVeF5wIRI6BGITSI69evr0VHBCUNRjHETQuiMWPGZIyQCk8++WSIy8izZMmS8NhBJOr8d3UQ/UeLlu5+/PHHwGBXX311Hahg0tWrV4c0ywCRnYvFI4DSF4go09ixYwMALLjtveJaEDF/47dCKk8Hkajz39VB9B8t2r5DjLvllltqzCvFg5i8nZEoxdAqsNIXMCyI9thjjyDCoZa3f4D+66+/rhuJHESiaHNXB1ET9KKXnjdvXpjIH3fccTX1tk3irbfeCpN9ev2HHnoovBKT54EIRQUKCwXb20s7lyfOoXC48sorA3AFoj///DNo4SgD8yfmN3nBR6I8yhR/7iAqTqsMhr3mmmtqI80555yTrVq1KigSmLSvWLEimzhxYnjPWhLrQwSBCC2ZnStpfgKzo15mrgXDM58ZOnRoSEcgQjRERBQwpFhAaSCVt0BEnlIsoNZ+9tlnQzkYKa+//vqwlnXaaaeFvNoB0a233hrS7fd/DqImOcCqjmHo1B8T8blz52YAi/DUU0/VqaaZr6DtYmLPZD5OY+rUqTUwCkQA+IYbbqjFlYobYI4bNy48tyCy5ZRqHZU0eVlgNQsiC2ali5Kln4ODqIXWZ8RAc4Va29rOsR7EWsvSpUvDqKWkYWisG2A6AAaIGMEIK1euDGszPCetOXPmhMVNLdIKRMQFlDfffHMGcAAD2sGnn346jDT8tiAiPvnaxVbynzBhQl35mgURYH7ggQdqZaDOjz/+eKhLv/5zEPVry3u9S6OAg6g0UnpC/UoBB1G/trzXuzQKOIhKI6Un1K8UcBD1a8t7vUujgIOoNFJ6Qv1KAQdRv7a817s0CjiISiOlJ9SvFHAQ9WvLe71Lo0BTIJo/f76fS2POpfGzmvysKngAXGAxkhdqb7bYYosQkcj+5zRwHqjnAfCRF2oggmgMWx6cAk6Bego0Jc45iOqJ57+cAlDAQeR84BRokwIOojYJ6J87BRxEzgNOgTYp4CBqk4D+uVPAQeQ84BRokwIOojYJ2InP5S4r9jfXibw9j4Ep4CAamEaFYuBJJ+/MopkzZwanJIUSSkTC3zc+47h66D4KOIhKaBN8WuP7DWcjOI2///77a+ZRuPjFAQlurSwI8CM3cuTISs4rKqFKnkQTFHAQNUGsvKgQcffdd89w6IiHnTi8/PLLwU2VnMjzHp9tsTPH+Dv/3RsUqBxEuHzC/dMXX3wRjvfA55l6bLyF2iAXT3JGKBdPy5Ytq0WTiyfSxREiPT/p4UaKs3s2bNgQ3Ehxdg+mSlxxK4WrJ4XYIX0qH+JqLoLzxUZBHks5USEVEPVwFI9nUpXf2p7Jfa9ohTdUnOILZCqH5kTKj9/UTY715XKLPBS4v+6662ourkgX5/S33377Ji629I1fm6NAR0AEox9//PHB+yZiDO518RGNOLN27dpQYhibc3BgBI4oAXSvvPJKxhlAVhQSEx511FHBU+hjjz0WmILDqzg14dJLLw0jAta1+IY78MADwyFXOkcV323ML8gHH25r1qzJ3nnnneB2F4CLUSmUmHcgEAEQ6ogfOh2IldcMgBlf2RyeBfPjxJHfPAdE48ePz4455pjsrLPOCsz/yy+/1MqhsglEHCTG6EddX3311dBJ0aGovKSJx1aeUWdoitfVUaNGBeeQsZ+6vDL788YU6AiIaMQnnniiriQ0NEwPqAic3kbPy9zCjho6VEuMIRDhptf6r2ZUYjTKOx5EDAgwyRc3uzZwbCQHXNljIu37ge6Z79DLA0QO1IKxOWfI1sWmAWA00ug5z3AfzChhvxOYVQeBiPLquEvS0BlGdCiMevJWGtfpk08+CR2Tg0iUb+/aERDttdde2VdffVVX0pgx6l6aH2KYGETxuTu45MVXNYxoQ5wPvqjzmId3zG0gSiuBUe7dd9/NZs2aFUYZOg9ABVPjM9sCIw9EqfzjOogmlNcGdTASD+UEX7RTXBQh559/fi4dFM+vxShQCojUyFbO5xkhxSw81zeKxzNGI8QY+Yy26YkRYkYJmZjT5QYCEe9tuvF9HsCUTzNXRgNERRzfM/oxZxOQUnRJPSO/mFYCkWiiMsW0ib9TPK4oNsqsq0273+5LARFiBOKL/eMZoShjIJrRqMwtSIeRBXEIWR8xTQwTM4oaTEc0kp8NMSPxnpHxww8/DOnznf1jfiNH9Daddu5Jb9KkSeG4yEZ0KUorB1E7rVH+t6WAqFGxijIGR4ugQEBet0FznbJAhAgEKO0RJza/Zu8RjZhn3XjjjXXzkzgd6GB7/hRdUs9IJ+4IioIILRwiJduXbXBxzlKj/fuuAREMFM+dpElD5JL83+5IpHkCx5RItIKM5DV9+vRwqhx5NBMAEMyKQgB1dhw4kQ4toVV6pACTekZarYKIxmWOZdenSA+xGe2oBXVcZv9dnAJdA6JHHnkkMCKaLam30SqhouXUbBQJMCNrSUycNXlWVYuKcwIma0OY4zDyad7CiXU6EIt0xbwaBZVXfKVMHMwFkFDJy2KBc4lQMjDyoWCwaTPy8ozjKRkxUPGXDSJGHPKhrpzwJxU3qnjmng6iuCVb+901IIK5GW1Yv2HkYQ0FNTSLp6znwAj05mj52gERZEottsL8b7zxRt3oVBRESpM1Kw7cAhxSWKAk4dh7rVOpmaQSJx7zQOZiZYOIvDh5DyBTJkBOXixy0zE4iNQa7V0rB1F7xfOvq6IANn2x+FxVXpt7ug6izbiFUbHfddddYa7G6KughWXEupStn+L5tRgFHETF6NSTsVCcYEKFFcQll1wSFnxl4oRo9+CDD/Zkvbqt0A6ibmuRksvDXJO5pYxUAc/o0aODksNqJ0vOtq+ScxD1VXN7ZauggIOoCqp6mn1FAQdRXzW3V7YKCjiIsqy2US5ewK2C4J7m5kcBB1GWhb03qIL5Qy3swSnQDAUcRM1QKxEX0LFfaCDToMSn/mgzoYCDqM2G1GZAB1GbhOzhzysHEWsRS5cuzSZMmBDs37AVY8sDzjNia+lVq1ZlZ5xxRoiHrRw+F1auXLmJrVwqTdnasS6iIKPUgeY6sWW4fmPLRpnwY0B5+OOeZwTZ1slOjivPPPQXBSoH0WuvvRaMH3FUwjYELInZhoBB5BVXXJFhaUyQsw+MIhcuXBgMTfGeg98CDE8tELCGxuKaHaM4+shLs10QYRYzceLEsB8Ho83bbrstGMiqLIhy2jRIncjP51T9BSBqWzmI5s6dG/au2M122hRmHXWwbYDV9NiBCL/p4cW4gI19ObHzDUYnGDm1sW+gZtXIozz0O3aGQh5YZFs/CHkb5AbK099vPhSoHER5pIrN/rEqTpnms/UBa2MxeOz9x6avd7jkaiYINMpDv4844oiwlcCmFW8hcBBZ6vTnfSkgajQ30N4dfMzZfTaMLnYkikGl5li/fn3YkCcGT+Vl5yTcNzvJF2iUR/xbZeHqILLU8HsoUAqI8hyVMMmfOnVqAA8jDSId8wb+cF7YDojYCau04isgaCbEoIl/27QcRJYafg8FSgFRHimZ9A8bNmwTh4zMLaZNm1YHIrYxE5dvbMgT53D5VFaIQRP/tvk4iCw1/B4KVAoizRfkZEQkx5EhCgC7s5J5DIoFFAw2sOeF5xK1cLk7duzY4K3Uev/kG9wGH3roocERh01joPsYNPFv+72DyFLD76FApSCCyQ855JAAGByvo4pGTYzaePbs2cGhIX4JYFp8cjNvwgsNYGAEwrcCqnH8AghEFBoVN/Mr3Ojirop08biDfwZ8TmutCDEPkdF+m2r2GDTxb/tNDCKNttSJDgCCeugvClQKIkiJQw5AwGgC42Miw2Ilf2wOQxEgv2jEBRiKK88/gMACIbXYOnz48GD7ZrdBdwJEAPbaa6+tLcbi6cdDf1GgchC1S06Jb/iO1sJsu2n6906BMinQNSDCp9zVV1+9idkMaz8seiKueXAKdCMFugZEcoDIguuCBQvC3II5xogRI8I8Ca+dHpwC3UiBrgERxOGALLySyoGjnUN1I/G8TE4BKNBVIPImcQr0IgUcRL3Yal7mrqKAg6irmsML04sUcBD1Yqt5mbuKAg6irmoOL0wvUqApEHFMCPZu/uc0cB74jwd0xnBeBzBELzDPwf8B1tf+5zRwHviPB8AF+MgLtTdEYtjy4BRwCtRToClxzkFUTzz/5RSAAg4i5wOnQJsUcBC1SUD/3CngIHIecAq0SQEHUZsE9M+dAn0Nonird6fZgR26nKnKOsPzzz+fjRo1qm57e6fL4/m1RoFBAxFbt/GOig9ttoOjQmfrw7hx47Jnnnkm++eff1qrURNfDTaIcLG8ww47ZPifILABcccdd/QDiZtow26IOiggwrkHDknkWITNd4sWLcrwJXfYYYcFQFk/3VUdX9IJEOWVHScu+JPAab/8QjAyXXPNNdnee++dffnll93AH16GAhSoBER4KbWOGeNy4Mhx6623rvXA9j2ednBmwpbw5cuXh1dVHV/SCRDllf2JJ54IIy/eimzAwSXuxHw7vKVKd98PCohwGYwYt2bNmiR1ABIOSuiZU26DeabnXG1IefghvTlz5tR2zJI3ItTtt9++if9vtqnjvQdGlogpD0XKRy61Wj16hZEHh/wpX99y9o9vPWjgofspMCggwiEj8x/EN4DSKOQdX1IURBKRmHfhkw4fdcw9OGeI+Zd1oi8/D7vssksoG6MIIwUiJqDCpRdBIGr16BWIzskSjMipgCNLjo6hnB66nwKDAiLrq43zh3DoiFfUvLN95EkV8UuhKIhWr16d7bvvvtmkSZNqTh1JQ0e0WBBxjAtiZixiMT9hnnLllVcG0AtErR69smTJkqBMwUllKgAeQNTs6RaptPxZ9RQoBURicsSfvL/UHAlGZjSiR5dzEkQt1L6MCgpKvxUQcbAYwLDfki4jFJbIApHEqFQ59U4ilkCUEsfieVaq7ICDMlG2VNA3sfvlVFx/NvgUKAVEP//8c/bCCy8EDRtaNs0pOPGO3/zR+0oLlao2TM18Bg+iiFN4TdWcSUxlgVB0JMqLRxlwii8QCRh5nQDPBTDFtV5ZVaciIIrj6FtdNa9jzuWh+ylQCojiasK4Yrj4XZHfb775ZhBnBJqqQERPH4MItTPzJhg5/mPkZP3KQVSkFfsnTsdBxFlGiGsALS8INOqJ9Vug4juNMPG8QipljRKaf9hv+T5PnGP+RBqNQrsgcnGuEXV7713HQaSJPiYuqQVFmBvVM+KTzm9NgUjP4nkDqmvmGwKRzjeKz3iVskAjEU0Hc6PFYw3HBhZGTzzxxIyDmJkftQsiATvuAJSnKxZEid64VgIiRptGcyAdjYKJy6xZs8KRJMybmA+hToaRTz755JpyIXV8iY5tAQR33313xuneHMVy0kkn1R3FAtNj/UCal1xySfbSSy9lHOcyfvz4XBU3Sg4WOxHr0NQh4qHiRoNIaAZEqbJDdFdx9wZAipSyEhAVyfjzzz8PJ3HLyQMjj2znYHKrhLAq8a222iqAjTzef//92rEtPOcISxifUUgjEfFg+nYWWzkjyfoCbwZEqbL7YmsRDumdOIMGot4hUTUlxV6QTiNek3Kzn2roXWWqDqIqqdsgbTdAbUCcHnvlIBrEBvOtEINI/BKzdhCVSMxmk0IT6ZvymqVa98V3EHVfm3iJeowCDqIeazAvbvdRwEHUfW3iJeoxCjiIGjQY1g4TJkwIC7V23anBJ139SlYesQlUVYVmUZ3FcKxI2MuFlYqMiqvKs5l0ZTrWyASN9BqtC/J+swZRUSLlEf6yyy4Lazm33HJLsIjA+qGXg05ox5qk6sDiNH40MOFCgZJS6VddhoHSZ5Ml4NZmy7z4fQMidonKYFXEaAdEItyxxx6brV+/Xkn2zDXPQUonKoCVBtYjbGfB8l0BlT6bDWPbRL3v1qt4IU8aqWQkgnnb2QrRLDFhcpi9ChDlEa7ZMnY6vqzZOyW62fphQMuuXxkQ653MndiEaTdd6n23XrsSRBTquuuuCz7WsJljizgiRiuOQyTnk47+xDipkQigAQxs7CZPnhzENYxT6TUxYiWk0hSYVPbhw4eH/LDZw2h28eLFQWwRIygfGIr6qVOhTMwTli1blmGBjrEr+TP3WrVqVbZu3brQi5Ou7AF5poBotHTp0hCf99QZ41joSdkIqrfowZVnqpfoQ1zSY+5C/ZUedUOEVXpKk3LjgQmDXzly4cpvRh+lxzZ6DgFjThkHLNfjXb0qry1X/F3eDmXiaWcADmUYgZupk2ij/GgD/G+I/txDN9pfPKC4unZ8JKKC+FaDceQ45LnnnguTzokTJ9Y2yVHAIo5DaLwVK1YE70GIEGykU+OrcbgqwNwwDEalMDGNwxYI5PeRI0dma9euDQwhpQLMzbYJPO8w4p166qmB8WXl/c477wQXX9jBwYwK5IOl+DHHHJOdddZZgcl/+eWXwMxYr+NvDqty8l+wYEGoNz30KaecEspFp4KICp1wcqmASERelJ9v6QxuuOGG8Ey++vKcu6RABACGDh2anXPOORl1senRPgIHNKTc5557bvBXwW/+KAegoA0J0Ilt9GJolVtXGA4LdruFhXRg5kYgghegT2oUww6ROnAlNFMnCyJET3iDzoJd2ShBcF9AffCx0TUgUq8R7++R4SUVoLEJRR2H5G2nVuNwVYC5YcxYLqcBbQ8JEOPeB2NR4sSNrUmzbWDyoWE1sVb+KhOAF4PSseDvgQa1IhDb7vHjYBsPQAF46KUgHxAa7XieAkz8DKYZM2ZMXfp8S3kApvX9lyq3zUeei7T1w4JE5eSqOuWBzMaN7+m4bJl4T92nTJmS7b///hlbcFqpk/gDEMIbjz76aF3WanfbDjZCKSORGgcmyPtTA+cNy2IEgUi/9Z0ttN7JcUizIEqJGmISETQFIhiF3pgtGHHg3bBhwzKYiACI6HEhsA3KRz233ll/D3qWKoPexVfys7RSm1jAx8/UFuQdB72bP39+eKVyxxsJY9rrO0b3VFCdUk5eUvHtM5XfOrbUpkt5YlL+zdRJbU4biv9svppfVgqiZhyVqDFUcFtYy0gidh4oeS6miRtSaabyipktL67yt4Tj27zt4/FIVjQf5c/3cQOmysDk/N577w2iJ2KdpY/oQZpiuEYgEn1iQNvvNcIobtxuMe3z4qmeXPNoY+Ok7lOKiXirvfJvpU555ZLiyvKCLV8pI5FNkHsqYhvUvlclucYhBaIijkPihlS6qbzyCBXHTTEw3w4miBD/pk6dGuY/MDciHXXnD/HQ0nxzBBHtCmgk0kmNb8VotWOZIJII2jUgYsKM3CkxQQwvEU29sX7nMa2+49opECHnNyPOWaZWedXIXG0oMhJpviHRRd9rTmXzKwIi+XJoRfRR3jHtJU5VIc6Rp+bUiHSaR9vRtp06sbgu/lP9uHZEnLMZcg+D2Aa176WdYTIIUBS0wm0rQUOklABM5K3jkLghlWaKYdsZiTTBZNIN4ypoMmt7xKL5KI0iIBIw4kk7vh9QNdu5nuJaBoufqdyM9tBUgboBVPX4PE/Rkucx7QX0uIxKW716K4oF0oBn4B1GhbvuuivU2ypZ2qkT8z3EY6vcIU+UUPBhR0eiRo5KIAKIRw8/b968oFJl6IUBUQVbEEnFPZDjEAh34IEHhj/8M8ihSKrhizJ3SpxDJj/vvPOCOIXnH1SgjVTcqY4kVSYaqgiIYPRDDjkkMA72aKijccHM0sDs2bOD5pD6U3YxM+/QOtF5xSAiX1S5tAVMzTeNVNwwGOW3IQZRVSpumydl4FwntJQpMLZaJ0YctJXwIGpypCac34wePbrzKm5b4dQ9vRFefpgYg3AtdKYYCSDJoyqNqDUS6ziEnhNPQVq4pBclpBi2HRCRJkCiB9RiK+VhLYjFUxuK5qNvUnVPARk7L+gF3cgbJmKBkD8aGxohKjN/gm5aNIQ+KRBBuzfeeCMsGBOXdFEX0xtLBU8ZU7TkeQwijWJ2VFQduba62GrT0GhDWbU2ZN+3U6euWWy1FWrmnslyHvGbScfjDi4FsGpAFIzFopR2bXBLWk7ulWjnGhUNjQo9OYuQEFUhtWCpd37tLQowgm1OBqgDUb/jIGKoxa8Aq/mYvTB/0byC4Zmzizz0PgWkKJLFhjpJe7xm79dyYw06DiKypadiqOcYFWR4wIM8j+0ZIPOweVCg2zfllUXlQQFRWYX3dJwC3UABB1E3tIKXoacp4CDq6ebzwncDBRxE3dAKXoaepkBXgShecMxb4CuL4nkLomWlr3RkecFxMdiWcRIGGspuUaKkFnVV9vhadZvE+fXC764GUVFvLK0SuhMgAijs5MUsCW87BGyxcNjBLtVuCFq7Y/2O+0bBQbQpdboaRJsWt9wnnQARVsVYftv1LxaZWS+JDT/LrV01qTmINqVrJSCC0Cnjy02zr38Si3P1b8v/VTWItHKPUSP2XjZgEY7tW8r2y8brtnsH0aYtMiggQgYvcnJd3GBapMVAkgVaFmoxBEUMkQmRTO0BCN57rLEmzjgkUkGKFIiw5J05c2YwZpXBq4w8+UZWynbbg8iK6IbxK9sSMM/XfpfUtgCV01oha27SqAPSRjT5FFDeurLPxvqKwFMQ9dl5550DvWTAizGqgvK1pv7QGkvm2KsPC6jQhbbxsJECHQeR5giAQN5+EHlwTTRu3Li6rRAxiBCJYBCYQkwKg8IYzDtIWwyBfwOYEYtmwEQ8rLytCBWDiNEC0GFij5cX9u8zUowYMSKYyAMwAozKnIZy2yDrYu2Vircu27jcxwa3KnsjEPEdZbLebZRu7BFHpv277LJLsHJn6wYjIC6+AIe2jChfCyJoTRsBcrZI8Ddp0qTgOMVBJIpvvHYcRNqZSIPQ2ymIAe1+ohhEMD0urGAWBYCDeT2j0YYNG2ogAmwwjA1xLx2D6M0330xaH2uzlnpfjTDxDlPew9yKx76pRlbpqW0Btrx596KhwKp4sp5GLCZgWgUd4q3SOjld38cgEhgPP/zwMPIqfVlhO4hEkY3XUkCkfSoQN+9Pvau2D6uhVRzAgNuoRiDCXRSjzj333FPzLafvdRVDyBOQnnON845BZOPa+xjM2l1pRSrKP2PGjDBi0SFI7EqVQ2krXcDUTFBebJ0HUAqMthIllX9qe73eoTGkrKKZRiKYgpEc+sSBreQOonqqlAIi5PsXXnghW7RoUfjTJjp2GOoZuwTpycQ46q1tcayjEp7HcckHE3vEDP5gYvKiZ1WIGULPuQrs8mATgwjmxLsoLok1h7Cdgi1zrBjQ6MBoR2hUDpVJ5Yk7FL1vdI3z11xNcyzln+dLnLrLpZfiCkSNysWo5iCqb5lSQFSf5Ebm18iTepfXCPSkjUYipUXvyVoLDiCZ57Ajk0kwIIgZQt9wFXPkgYgRgbROOumkIAqya5M/tlzHZRbTygkl8xRU2YhUhEblUJlUnlZApPwlkjHKWm2f8i8bRLFoq7r087XjIJK3n5hxAMBA4lyqoZDf6X019xDzpJwDNhLnfv/99wyLgpQ6Oq/3ZdRBfGJRGGYWoCinRKYqxDnRgfwR11CAMD+z4iUi5/nnn5908aWy5Ylz8s/g4pwo3fjacRDJY6VlOIqoyW7eSMToQ6OiNYsDYqC8jwpEbE+OtWeNFAv6LgYfIAVcjETx3EUKBmnZ4vdVKRZUf0Y9Rr+HH344+IuOFR0oFhB7Y8T7eYgAAAIZSURBVJfJKrdGMdVd4pzU73GHoo118ais8vTrtRIQDeTtB8frNC47W1966aUgLuH8vZGKG00eKnHEN8Q+GAHPNHIGrx2TYgi8wbDRDzEL1S7zMwCKQ3riEOI5EYoLyoUXIsDOfA5tICcuANKLLrooTMQZNQlSMMBU8SSf91WpuEPmRmRkcyN0YaS1gY4HDRv1pv6ovIuquBGPoQWj/PPPPx/oiLN92slBZKk8SCflwcStLLbyHQwtTzs0JvcoF6T2FojoVQGoXWzlKBV7TEkMItKYPn16mFvAQNpti6iH5o1njEr8VoApUSPHowDv1eMD+jiot5cigPcqe958Mk6D34w20CG1+Mt76sQamhQlgA3XZHi1UVC+Gol47outos7A10pGooGzrS5GiiGqy23jwqdVKNi8NFLFYhFxYu2a/c7ve4sCDqI22oteHkuLeH5nk9zcDFBt3fx+IwUcRC1wAvMltIyIYtZ8JpUU86du3wqRKrc/K04BB1FxWtViop5nHsKEHjANFBixmEvxx+S/2zblDVR+f9+YApsdiBpX1986BcqngIOofJp6in1GAQdRnzW4V7d8CjiIyqepp9hnFHAQ9VmDe3XLp0BTIEIj5X9OA+eBNA/kwXNI3gt/7hRwChSjgIOoGJ08llMglwIOolzS+AunQDEKOIiK0cljOQVyKeAgyiWNv3AKFKOAg6gYnTyWUyCXAv8HOiUJRhUro/kAAAAASUVORK5CYII=)

Giải thích: hình trên là mô tả của lớp `Student` với các thuộc tính và phương thức giống như sau:

-   `name` là thuộc tính kiểu `string` với phạm vi truy cập `private`.
-   `age` là thuộc tính kiểu `int` với phạm vi truy cập `private`.
-   `Student()` là phương thức khởi tạo không tham số có phạm vi truy cập là `public`.
-   `getInformation()` và `display()` là hai phương thức có phạm vi truy cập `public`.

Trong thực tế, bạn nên tách các class ra thành các file riêng, mỗi class sẽ tương ứng với một file, cửa sổ code trong bài này chính là file `Student.cpp`, trong file này bạn cần tạo ra lớp `Student` với đầy đủ các thuộc tính và phương thức giống như đã mô tả (bạn chỉ cần khai báo các thuộc tính và phương thức, không cần viết code bên trong phương thức).

Lưu ý: bạn cần đặt tên file đúng theo yêu cầu, phân biệt in hoa và in thường. Ví dụ các tên file như `student.cpp, a.cpp, s.cpp` đều không được chấp nhận.

### Lý thuyết

Hình minh họa về lớp `Student` bên trên chính là một sơ đồ lớp. Ở các bài trước bạn đã được làm quen với sơ đồ này nhưng ở bài này bạn sẽ được hiểu sâu hơn về nó.

Sơ đồ lớp

Như bạn đã biết, lập trình hướng đối tượng là phương pháp giải quyết các bài toán lập trình thông qua các đối tượng và mối quan hệ giữa chúng, một chương trình thực tế sẽ có rất nhiều các lớp và đối tượng. Sơ đồ lớp chính là sơ đồ mà nhìn vào đó bạn thấy được mô tả của các lớp, mối quan hệ giữa các đối tượng trong hệ thống (mối quan hệ giữa các đối tượng bạn sẽ được học trong các bài tiếp theo).

Một ký hiệu lớp sẽ có 3 phần là Class name (tên lớp), attributes (danh sách các thuộc tính) và operations (các thủ tục, để đơn giản thì bạn hãy coi thủ tục chính là phương thức). Một lớp trong biểu đồ lớp sẽ được mô tả giống như sau:

![](data:image/png;base64,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)

Trong sơ đồ lớp, bạn có thể mô tả phạm vi truy cập của các thuộc tính, phương thức bằng cách đặt các ký tự `-, #, +` trước các thuộc tính và phương thức.

-   Ký tự `'-'` sẽ tương ứng với phạm vi truy cập `private`.
-   Ký tự `'#'` sẽ tương ứng với phạm vi truy cập `protected`.
-   Ký tự `'+'` sẽ tương ứng với phạm vi truy cập `public`.

Ví dụ lớp `Student` giống như sau:

```
class Student {
	string name;
private:
	int id;
protected:
	int age;
public:
	double gpa;

	Student() {

	}

	void getInformation() {

	}

	void display() {

	}
};
```

Sẽ được biểu mô tả bằng sơ đồ lớp giống như sau (bạn hãy để ý các ký tự `-, #, +`):

![](https://codelearn.io/Media/Default/Users/TuanLQ7/Java_OOP/class8.png)

Lưu ý: khi một phương thức không được định nghĩa kiểu trả về và tên phương thức trùng với tên lớp thì đây chính là phương thức khởi tạo. Như trong sơ đồ lớp trên thì `+Student()` chính là phương thức khởi tạo `public`. Ngoài ra, nếu một phương thức hay thuộc tính không được khai báo kiểu trả về thì mặc định phạm vi truy cập của nó sẽ là `private`.

Để chắc chắn rằng bạn đã hiểu về sơ đồ lớp, hãy xem ví dụ tiếp theo về lớp `Product` (lớp dùng để mô tả các đối tượng sản phẩm):

```
class Product {
	string description;
private:
	string name;	
protected:
	double price;
public:
	int id;
	Product() {

	}
	void getInformation() {
	}
	void display() {
	}
}
```

Lớp này sẽ được mô tả bằng sơ đồ lớp giống như sau:

![](https://codelearn.io/Media/Default/Users/TuanLQ7/Cpp_OOP/class8.png)

Đọc tới đây bạn đã hiểu được cách mô tả các lớp bằng ký hiệu lớp, hãy quay lại phần bài tập và làm thử.

### Hướng dẫn

Code mẫu:

```
#include<iostream>

using namespace std;

class Student {
private:
	string name;
	int age;
public:
	Student() {

	}

	void getInformation() {
	}

	void display() {
	}
};
```