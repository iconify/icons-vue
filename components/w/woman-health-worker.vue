<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isiDy1U)"><path fill="url(#ii0BdZd)" clip-rule="evenodd" class="hxpkmrbhv"/><path fill="url(#i9GmtLd)" clip-rule="evenodd" class="hxpkmrbhv"/><path fill="url(#irgPSub)" clip-rule="evenodd" class="hxpkmrbhv"/><path fill="url(#i1m9xrc)" clip-rule="evenodd" class="hxpkmrbhv"/><path fill="url(#inLtJOc)" clip-rule="evenodd" class="hxpkmrbhv"/><path fill="url(#iCCvV5d)" clip-rule="evenodd" class="hxpkmrbhv"/><path fill="url(#itLYrMd)" clip-rule="evenodd" class="hxpkmrbhv"/><path fill="url(#iPhWIhO)" clip-rule="evenodd" class="hxpkmrbhv"/></g><path fill="url(#inrTjie)" class="w6adskb0e"/><path fill="url(#isdpLLe)" class="w6adskb0e"/><path fill="url(#iRHZgDb)" class="w6adskb0e"/><path fill="url(#iQEKroc)" class="w6adskb0e"/><path fill="url(#iLgPmtd)" class="w6adskb0e"/><path fill="url(#i6cwD0b)" class="w6adskb0e"/><path fill="url(#iASsVeD)" class="w6adskb0e"/><path fill="url(#ifKzXly)" class="sn8_yabny"/><path fill="url(#iva8Lge)" class="fwo4edbae"/><path fill="url(#i29xuLp)" class="sfyznbc9r"/><path fill="url(#iBBbYOc)" class="sfyznbc9r"/><path fill="url(#iO2ynnd)" class="sfyznbc9r"/><path fill="url(#iAeo9ie)" class="azprm0ban"/><path fill="url(#iazZBde)" class="azprm0ban"/><path fill="url(#iSB6lNe)" class="azprm0ban"/><path fill="url(#i7MdG0b)" class="xte6pybex"/><path fill="url(#iPeSqYc)" class="xte6pybex"/><path fill="url(#ifKzXly)" class="sn8_yabny"/><path fill="url(#iva8Lge)" class="fwo4edbae"/><g filter="url(#iHn4Qyd)"><path class="x_qr5mb8u"/></g><g filter="url(#iPFHfJd)"><path fill="url(#idFIgOR)" class="g48b8nbdp"/></g><path fill="url(#iprkURc)" class="vl_71zbpn"/><path fill="url(#i7vF7xj)" class="vl_71zbpn"/><path fill="url(#ipi3IZG)" class="vl_71zbpn"/><path fill="url(#i7y4Qeo)" class="vl_71zbpn"/><path fill="url(#ipX5PZd)" class="vl_71zbpn"/><path fill="url(#i8PpvEb)" class="vl_71zbpn"/><path fill="url(#issfy2c)" class="qfcob2xqa"/><path fill="url(#iau8Ige)" class="qfcob2xqa"/><path fill="url(#ijLGIpb)" class="qfcob2xqa"/><path fill="url(#ibsiGBc)" class="qfcob2xqa"/><path fill="url(#irumxzy)" class="qfcob2xqa"/><path fill="url(#iy5Bypb)" class="qfcob2xqa"/><path fill="url(#i0CBfnd)" class="is0assbdf"/><path clip-rule="evenodd" class="zx8nkmr9v"/><path fill="url(#i3oIolu)" clip-rule="evenodd" class="cfatuc8ry"/><path fill="url(#i9UNX3b)" clip-rule="evenodd" class="cfatuc8ry"/><path fill="url(#i4Ws36d)" clip-rule="evenodd" class="cfatuc8ry"/><path fill="url(#i5To5Nd)" clip-rule="evenodd" class="cfatuc8ry"/><g filter="url(#ib3mAJd)"><path class="z0appneii"/></g><path fill="url(#ieqjsye)" class="k0m7kbc0w"/><g filter="url(#iJnPrhm)"><path fill="url(#imbyHXd)" class="q6yg1dbri"/></g><g filter="url(#iCENazg)"><path fill="url(#ijmHDme)" clip-rule="evenodd" class="n0wj2bo6u"/></g><g filter="url(#iNIUEje)"><path class="epwsh45db"/></g><path fill="url(#izBzxcc)" clip-rule="evenodd" class="qv5iz7s5h"/><path fill="url(#iyES09U)" clip-rule="evenodd" class="qv5iz7s5h"/><path fill="url(#iIcALBd)" clip-rule="evenodd" class="s63n20c1j"/><path fill="url(#ieVVO6b)" clip-rule="evenodd" class="s63n20c1j"/><g filter="url(#ikVbBjc)"><path fill="url(#ikZYwcD)" class="strpvsbcu"/></g><g filter="url(#inRWUBc)"><path fill="url(#i6nnODe)" class="i4oiov80o"/></g><g filter="url(#isYSISc)"><path class="pyzag196p"/><path fill="url(#isP6dwc)" class="k-h0q1_ly"/></g><g filter="url(#ijfJCAb)"><path class="p91z4eb9u"/><path fill="url(#ijqbsvb)" class="l1666bc-t"/></g><g filter="url(#iRAK9Hb)"><path fill="url(#itSauCc)" class="yot0t3b3a"/><path fill="url(#inbPBue)" class="yot0t3b3a"/><path fill="url(#idhOlGF)" class="yot0t3b3a"/><path fill="url(#iNxcb8b)" class="yot0t3b3a"/><path fill="url(#iOjHnJL)" class="yot0t3b3a"/><path fill="url(#i5dfKJe)" class="yot0t3b3a"/><path fill="url(#isAgG4c)" class="yot0t3b3a"/></g><path fill="url(#iPFGJDb)" class="yot0t3b3a"/><g filter="url(#iucwSVw)"><path class="dl83qu84x"/></g><g filter="url(#ibrIOKb)"><path fill="url(#iMkfaDb)" class="gvnsstb3n"/><path fill="url(#ixjR3fR)" class="gvnsstb3n"/><path fill="url(#iVCuh4L)" class="gvnsstb3n"/><path fill="url(#ixG1h6d)" class="gvnsstb3n"/></g><path fill="url(#iRpErAe)" class="gvnsstb3n"/><path fill="url(#iBDh2Kd)" class="gvnsstb3n"/><path stroke="url(#iZz3Goc)" class="rtni5gbbr"/><g filter="url(#iAbuR5c)"><path class="hb6v9bbzb"/></g><g filter="url(#ilOE25p)"><path class="m7dv8bc9y"/></g><g filter="url(#iAvw4zc)"><path class="qbzsgpbjh"/></g><g filter="url(#izEcrwc)"><path clip-rule="evenodd" class="cupi42bbn"/></g><path class="ke6p8h_al"/><path fill="url(#iXk9aNe)" class="krf5fdc8x"/><path class="iy8i9cc7x"/><g filter="url(#iop4Jlb)"><path class="bxww_4bnc"/><path fill="url(#izO85cb)" class="rnuxyvz7r"/></g><g filter="url(#i5ub9Xd)"><path fill="url(#itxuE0d)" class="cowumdwfi"/></g><path class="ap37acbhm"/><path fill="url(#ixsehMs)" class="lmk1trbwl"/><path class="q35w0ghnv"/><g filter="url(#iE70M6c)"><path fill="url(#ipskavd)" class="lv0ekyn2w"/></g><g filter="url(#iH7qtOb)"><ellipse transform="rotate(-27.914 13.44 9.937)" class="sww2dpbzr"/><ellipse fill="url(#i5TRIxc)" transform="rotate(-27.914 13.44 9.937)" class="v47zn3bio"/></g><g filter="url(#igFsuic)"><path class="k-ij1-bto"/></g><g filter="url(#i3emvUc)"><path class="mbxx3sy2o"/></g><g filter="url(#iOnb7Wc)"><path fill="url(#i1mp7GI)" class="pwflswk8e"/><path fill="url(#iWuvWPd)" class="pwflswk8e"/></g><g filter="url(#ij7J49d)"><path fill="url(#iUdgmkb)" class="epit8zb-h"/><path fill="url(#ipR3XNe)" class="epit8zb-h"/><path fill="url(#iHF1Nse)" class="epit8zb-h"/></g><g filter="url(#iZxPeYo)"><path stroke="url(#iWfLwZB)" class="xzelkqbsb"/></g><defs><radialGradient id="i9GmtLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45645 -2.68487 0 11.325 12.665)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="irgPSub" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.57099 -5.8032 0 15.894 12.756)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="i1m9xrc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24075 1.61016 -1.56338 -1.2047 10.983 10.951)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="inLtJOc" cx="0" cy="0" r="1" gradientTransform="rotate(100.537 2.249 9.067)scale(2.55689 2.06985)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="c42_rqbzh"/><stop offset="1" class="ybrvbdb9p"/></radialGradient><radialGradient id="iCCvV5d" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 3.428 12.06)scale(2.38097 4.53569)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="itLYrMd" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.622 7.147)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="iPhWIhO" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.403 9.779)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="inrTjie" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.089 23.931)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="iLgPmtd" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.103 8.212)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="i6cwD0b" cx="0" cy="0" r="1" gradientTransform="rotate(77.152 -6.382 23.496)scale(3.65398 4.0429)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="iASsVeD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.86 30)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="i29xuLp" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.226 24.712)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="iBBbYOc" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.767 12.296)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="iAeo9ie" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.125 21.962)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="iazZBde" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.444 20.328)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="i7MdG0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 15.896 18.558)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="oz5ru-b9o"/><stop offset="1" class="c7u_gdcjm"/></radialGradient><radialGradient id="iPeSqYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.258 30.494)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="p5_0bzbaz"/><stop offset="1" class="iqq-d2brk"/></radialGradient><radialGradient id="i7y4Qeo" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 19.032 18.119)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="ipX5PZd" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.34 26.56)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="i8PpvEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.032 24.869)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="issfy2c" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.327 11.27)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="iau8Ige" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.024 24.923)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="ibsiGBc" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.195 19.494)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="irumxzy" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 11.992 18.322)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="iy5Bypb" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -17.084 24.111)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="i0CBfnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.21875 3.80462 0 15.879 18.15)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ctwb9kb3f"/><stop offset=".932" class="b9pxxabdi"/></radialGradient><radialGradient id="i9UNX3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.30438 0 18.398 16.384)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ad-0z61hw"/><stop offset="1" class="p6pfsuaja"/></radialGradient><radialGradient id="i4Ws36d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.476 20.04)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="i5To5Nd" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.763 12.162)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="s96-1fbmn"/><stop offset="1" class="pvle9ybys"/></radialGradient><radialGradient id="ieqjsye" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.1 18.037)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="imbyHXd" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.142 25.908)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="iyES09U" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.024 23.572)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="i6nnODe" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 19.933 11.07)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="isP6dwc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.6 -51.79)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="ijqbsvb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.228 10.63)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="itSauCc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.753 10.092)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="inbPBue" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.794 10.79)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="idhOlGF" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.715 16.875)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iNxcb8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.44059 -11.8177 0 15.632 9.609)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="iOjHnJL" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.521 11.749)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="i5dfKJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.195 9.674)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="isAgG4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 13.976 9.761)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iPFGJDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 20.99 11.162)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="ixjR3fR" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.678 11.888)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iBDh2Kd" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.243 8.358)scale(1.57489 2.10945)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iXk9aNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.076 10.033)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="izO85cb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.401 .688)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixsehMs" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.712 10.033)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i5TRIxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.425 10.252)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1mp7GI" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 5.723 4.943)scale(5.36951 2.34181)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iWuvWPd" cx="0" cy="0" r="1" gradientTransform="rotate(146.397 5.892 4.298)scale(2.63581 1.30471)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iUdgmkb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18534 4.55504 -6.4674 -3.10282 17.685 2.505)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="ipR3XNe" cx="0" cy="0" r="1" gradientTransform="matrix(-.94295 3.30827 -6.9331 -1.97612 18.403 3.758)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iHF1Nse" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41682 -6.46743 5.78149 -3.05443 17.044 9.39)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><linearGradient id="ii0BdZd" x1="20.587" x2="13.346" y1="3.678" y2="17.12" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="isdpLLe" x1="23.203" x2="22.89" y1="24.611" y2="24.611" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iRHZgDb" x1="8.625" x2="8.961" y1="24.611" y2="24.611" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="iQEKroc" x1="16.07" x2="16.07" y1="30.963" y2="29.15" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="ifKzXly" x1="8.709" x2="23.085" y1="15.44" y2="15.44" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iva8Lge" x1="8.709" x2="23.085" y1="15.409" y2="15.409" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iO2ynnd" x1="6.889" x2="6.889" y1="30.775" y2="29.315" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iSB6lNe" x1="22.56" x2="23.338" y1="25.649" y2="25.649" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="idFIgOR" x1="16.07" x2="23.695" y1="26.994" y2="19.4" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="iprkURc" x1="21.784" x2="16.669" y1="18.389" y2="23.907" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="i7vF7xj" x1="19.938" x2="19.781" y1="15.67" y2="17.733" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="ipi3IZG" x1="17.476" x2="18.633" y1="18.915" y2="19.4" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="ijLGIpb" x1="12.164" x2="12.492" y1="23.212" y2="22.853" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="i3oIolu" x1="20.203" x2="19.531" y1="23.681" y2="23.697" gradientUnits="userSpaceOnUse"><stop offset=".294" class="w_l8deb9l"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="ijmHDme" x1="12.099" x2="12.099" y1="19.879" y2="28.462" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="izBzxcc" x1="9.408" x2="10.302" y1="25.279" y2="25.279" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iIcALBd" x1="13.781" x2="14.453" y1="25.289" y2="25.289" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="ieVVO6b" x1="14.844" x2="14.601" y1="24.806" y2="24.806" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="ikZYwcD" x1="9.599" x2="12.558" y1="10.717" y2="10.717" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iMkfaDb" x1="15.894" x2="15.894" y1="12.668" y2="9.986" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iVCuh4L" x1="14.848" x2="15.702" y1="11.906" y2="12.01" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="ixG1h6d" x1="15.894" x2="15.894" y1="12.76" y2="12.15" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iRpErAe" x1="15.972" x2="15.972" y1="12.734" y2="12.595" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iZz3Goc" x1="15.165" x2="15.617" y1="14.237" y2="13.366" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="itxuE0d" x1="18.854" x2="18.54" y1="10.087" y2="10.28" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipskavd" x1="14.455" x2="14.142" y1="10.086" y2="10.28" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWfLwZB" x1="13.003" x2="13.547" y1="4.431" y2="5.705" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><filter id="isiDy1U" width="15.268" height="15.268" x="8.385" y="1.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24142"/></filter><filter id="iHn4Qyd" width="7.147" height="11.557" x="8.923" y="15.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".5"/></filter><filter id="iPFHfJd" width="7.147" height="11.557" x="15.818" y="15.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".5"/></filter><filter id="ib3mAJd" width="3.699" height="3.699" x="16.889" y="24.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".375"/></filter><filter id="iJnPrhm" width="1.42" height="1.42" x="18.859" y="24.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24142"/></filter><filter id="iCENazg" width="5.381" height="7.171" x="9.408" y="19.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24142"/></filter><filter id="iNIUEje" width="5.3" height="6.89" x="9.474" y="19.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".15"/></filter><filter id="ikVbBjc" width="3.368" height="3.468" x="9.599" y="9.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.627451 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24142"/></filter><filter id="inRWUBc" width="3.218" height="3.468" x="19.112" y="8.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24142"/></filter><filter id="isYSISc" width="3.148" height="3.148" x="19.147" y="9.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".25"/></filter><filter id="ijfJCAb" width="2.648" height="2.648" x="9.903" y="9.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".125"/></filter><filter id="iRAK9Hb" width="10.191" height="11.077" x="10.799" y="5.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24142"/></filter><filter id="iucwSVw" width="2.877" height="3.682" x="14.293" y="9.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".25"/></filter><filter id="ibrIOKb" width="2.377" height="3.182" x="14.705" y="9.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".125"/></filter><filter id="iAbuR5c" width="3.001" height="1.286" x="16.836" y="9.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24142"/></filter><filter id="ilOE25p" width="3.001" height="1.286" x="11.951" y="9.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24142"/></filter><filter id="iAvw4zc" width="2.453" height="1.091" x="12.086" y="7.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24142"/></filter><filter id="izEcrwc" width="2.453" height="1.091" x="17.503" y="7.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24142"/></filter><filter id="iop4Jlb" width=".786" height=".696" x="17.342" y="9.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".05"/></filter><filter id="i5ub9Xd" width=".891" height=".913" x="18.182" y="9.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".1"/></filter><filter id="iE70M6c" width=".986" height="1.04" x="13.739" y="9.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".1"/></filter><filter id="iH7qtOb" width=".912" height=".704" x="12.984" y="9.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".05"/></filter><filter id="igFsuic" width="2.861" height="1.578" x="17.233" y="7.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".2"/></filter><filter id="i3emvUc" width="2.861" height="1.578" x="11.782" y="7.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".2"/></filter><filter id="iOnb7Wc" width="4.985" height="5.213" x="9.186" y="3.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".375"/></filter><filter id="ij7J49d" width="8.914" height="5.78" x="12.577" y="2.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".125"/></filter><filter id="iZxPeYo" width="1.145" height="2.31" x="12.703" y="3.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24142" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-health-worker" /></template>
<style>
.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ad-0z61hw {
  stop-color: var(--svg-color--552e54, #552E54);
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.ap37acbhm {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.503 9.284c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.azprm0ban {
  d: path("M26.72 27.97c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59V30h3.65z");
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.b9pxxabdi {
  stop-color: var(--svg-color--a5630d, #A5630D);
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.bxww_4bnc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.012 9.745c.063.085-.07.189-.22.302c-.151.112-.264.192-.327.107c-.064-.085.007-.246.158-.358c.151-.113.325-.136.389-.051");
}

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c42_rqbzh {
  stop-color: var(--svg-color--d77016, #D77016);
}

.c7u_gdcjm {
  stop-color: var(--svg-color--512c71, #512C71);
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.cfatuc8ry {
  fill-rule: evenodd;
  d: path("M15.829 15.12a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 1 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cowumdwfi {
  d: path("M18.873 10.33a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.ctwb9kb3f {
  stop-color: var(--svg-color--f1a128, #F1A128);
}

.cupi42bbn {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.626 8.395l-.138.23za.268.268 0 0 1-.275.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dl83qu84x {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.501 10.407l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dxszyubmb {
  stop-color: var(--svg-color--d3cfda, #D3CFDA);
}

.e---z_byu {
  stop-color: var(--svg-color--ad9ec2, #AD9EC2);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.epit8zb-h {
  d: path("M15.29 2.84c-1.132-.25-2.346.955-2.463 1.374c1.542 3.62 3.91 3.275 6.537 2.983c1.572-.174 1.743.542 1.877.889c-.436-4.056-3.37-4.677-5.95-5.247");
}

.epwsh45db {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.084 26.294h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.foe4l_bip {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
  stop-opacity: 0;
}

.fr_rdtj9g {
  stop-color: var(--svg-color--d4cae9, #D4CAE9);
}

.ft5dv1b6b {
  fill: none;
}

.fwo4edbae {
  d: path("M15.919 15.41h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.g48b8nbdp {
  d: path("m21.787 20.154l-.732.13a.213.213 0 0 0-.12.352l.704.77a.216.216 0 0 1-.01.297l-4.506 4.599c-.11.11-.305.037-.305-.121v-3.329c0-.037.009-.064.018-.102l2.54-5.887a.15.15 0 0 1 .038-.065a9.7 9.7 0 0 1 2.364 1.122l.186 2.002a.215.215 0 0 1-.177.232");
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gvnsstb3n {
  d: path("m15.512 10.269l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hb6v9bbzb {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.036 10.061c.265-.467.669-.835 1.537-.835c.38 0 .747.105 1.073.368c.269.218.233.495.025.6l-.556.317c-.652-.21-1.373-.24-2.079-.45");
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.hxpkmrbhv {
  fill-rule: evenodd;
  d: path("M23.08 12.04a3.25 3.25 0 0 0 .323-1.427a3.3 3.3 0 0 0-.268-1.305h.005a3 3 0 0 0-.281-.513l-.003-.004a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001A3.3 3.3 0 0 0 9.458 7.01v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.51.51 0 0 1 0-.455M10.818 9.368h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.955-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.19 1.235l-.051.02l-.051.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.i4oiov80o {
  d: path("M20.721 12.24a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.218");
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.iqq-d2brk {
  stop-color: var(--svg-color--574379, #574379);
  stop-opacity: 0;
}

.is0assbdf {
  d: path("M15.879 18.72a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.iy8i9cc7x {
  fill: var(--svg-color--000, #000);
  d: path("M17.567 10.448c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.k-h0q1_ly {
  d: path("M20.721 11.704a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.k-ij1-bto {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.833 8.257c.323-.078 1.125-.039 1.661.345");
}

.k0m7kbc0w {
  d: path("M19.569 26.73a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.ke6p8h_al {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.285 9.284c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.krf5fdc8x {
  d: path("M18.078 9.556a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv70nqbkg {
  stop-color: var(--svg-color--b49089, #B49089);
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l-etq6b9a {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
}

.l1666bc-t {
  d: path("M11.228 11.704a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll7oxmbau {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
  stop-opacity: 0;
}

.lmk1trbwl {
  d: path("M13.71 9.556a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.lnyefdcqm {
  stop-color: var(--svg-color--c8bfd6, #C8BFD6);
}

.lpc21p-wa {
  stop-color: var(--svg-color--553c83, #553C83);
}

.lv0ekyn2w {
  d: path("M14.525 10.343c0-.288-.235-.48-.298-.538l-.288.278l.177.361z");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m7dv8bc9y {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.752 10.061c-.266-.467-.669-.835-1.537-.835c-.38 0-.747.105-1.073.368c-.269.218-.233.495-.025.6l.556.317c.652-.21 1.373-.24 2.079-.45");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbxx3sy2o {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.043 8.257c-.323-.078-1.125-.039-1.661.345");
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.n0wj2bo6u {
  fill-rule: evenodd;
  d: path("M12.099 20.86c-.94 0-1.71.762-1.71 1.71v3.3h.67a.49.49 0 1 1 0 .98h-1a.65.65 0 0 1-.65-.65v-3.63a2.69 2.69 0 0 1 5.38 0v3.63c0 .36-.29.65-.65.65h-.93a.49.49 0 0 1 0-.98h.6v-3.3c0-.94-.762-1.71-1.71-1.71");
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o874sbcxz {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
}

.oc1bwblbr {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oz5ru-b9o {
  stop-color: var(--svg-color--785998, #785998);
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p5_0bzbaz {
  stop-color: var(--svg-color--574379, #574379);
}

.p6pfsuaja {
  stop-color: var(--svg-color--552e54, #552E54);
  stop-opacity: 0;
}

.p91z4eb9u {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.228 11.704a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pvle9ybys {
  stop-color: var(--svg-color--4a2657, #4A2657);
  stop-opacity: 0;
}

.pwflswk8e {
  d: path("M11 4.616c.62-.553 1.517-.559 2.02-.47l.402 1.291c-.257-.039-.486.05-.68.235c-.455 1.26-2.022 1.956-2.748 2.146c-.15-1.492-.067-2.246 1.006-3.202");
}

.pyzag196p {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.721 11.704a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q35w0ghnv {
  fill: var(--svg-color--000, #000);
  d: path("M14.22 10.448a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.q6yg1dbri {
  d: path("M19.569 26.18a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qbzsgpbjh {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.496 8.852l-.004.003a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.815-.2 1.328-.11a.268.268 0 0 1-.093.53a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.456.193");
}

.qfcob2xqa {
  d: path("M15.264 21.691c.263.516.263.942.263 1.306v2.99c0 .17-.209.26-.328.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.119-.13.05-.35-.129-.38l-.783-.14a.23.23 0 0 1-.188-.25l.187-2.058a.25.25 0 0 1 .113-.187a10.5 10.5 0 0 1 2.426-1.134a.3.3 0 0 1 .04.08z");
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qv5iz7s5h {
  fill-rule: evenodd;
  d: path("M9.408 26.19v-2.47h.982v2.14h.249v.98h-.58a.65.65 0 0 1-.65-.65");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rnuxyvz7r {
  d: path("M18.012 9.745c.063.085-.07.189-.22.302c-.151.112-.264.192-.327.107c-.064-.085.007-.246.158-.358c.151-.113.325-.136.389-.051");
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.rtni5gbbr {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.496 13.153a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.247-.042c-.404.216-.88.34-1.398.34a3 3 0 0 1-1.398-.34Z");
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s63n20c1j {
  fill-rule: evenodd;
  d: path("M14.79 23.73v2.47c0 .36-.29.65-.651.65h-.58v-.98h.25v-2.14z");
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.s96-1fbmn {
  stop-color: var(--svg-color--4a2657, #4A2657);
}

.sfyznbc9r {
  d: path("m5.82 22.77l-.03.08C5.27 24.5 5 26.21 5 27.94V30h3.67V18.25a10.56 10.56 0 0 0-2.85 4.52");
}

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.sn8_yabny {
  d: path("M16.249 15.41c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.sp4_sibjj {
  stop-color: var(--svg-color--5d4f77, #5D4F77);
}

.strpvsbcu {
  d: path("M11.208 12.24a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.218");
}

.sww2dpbzr {
  cx: 13.44px;
  cy: 9.937px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v47zn3bio {
  cx: 13.44px;
  cy: 9.937px;
  rx: 0.389px;
  ry: 0.197px;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.vl_71zbpn {
  d: path("M16.543 21.691c-.262.516-.262.942-.262 1.306v2.99c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.753-.83a.23.23 0 0 1 .129-.38l.783-.14a.23.23 0 0 0 .188-.25l-.187-2.058a.25.25 0 0 0-.113-.187a10.5 10.5 0 0 0-2.426-1.134a.3.3 0 0 0-.04.08z");
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.w_l8deb9l {
  stop-color: var(--svg-color--746992, #746992);
}

.w-_6jxb_z {
  stop-color: var(--svg-color--efeafb, #EFEAFB);
}

.w0rhj52ia {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w6adskb0e {
  d: path("M15.88 15.41c-2.74 0-5.3 1.06-7.21 2.84V30h14.38V18.22a10.54 10.54 0 0 0-7.17-2.81");
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
}

.x_qr5mb8u {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.1 20.154l.733.13a.213.213 0 0 1 .12.352l-.704.77a.216.216 0 0 0 .009.297l4.506 4.599c.111.11.306.037.306-.121v-3.329c0-.037-.01-.064-.018-.102l-2.54-5.887a.15.15 0 0 0-.038-.065a9.7 9.7 0 0 0-2.364 1.122l-.186 2.002a.214.214 0 0 0 .176.232");
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x3e-lhbqh {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
  stop-opacity: 0;
}

.x7yaztbkk {
  stop-color: var(--svg-color--b3a299, #B3A299);
  stop-opacity: 0;
}

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.xte6pybex {
  d: path("M16.387 22.514c0-.04-.01-.203 0-.243l2.662-6.29c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.36c.01.03.055.05.055.09l.055 3.6h.01V30h.79v-3.97l.078-3.416z");
}

.xzelkqbsb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.003 4.088c.023.243.234 1.156.544 1.71");
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.ybrvbdb9p {
  stop-color: var(--svg-color--d77016, #D77016);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yot0t3b3a {
  d: path("M10.807 9.367h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439q.024-.008.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.082.088 1.135 1.333l-.118 3.073c-.124 2.802-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z0appneii {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.738 26.959a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.zx8nkmr9v {
  fill: var(--svg-color--5a4b7e, #5A4B7E);
  fill-rule: evenodd;
  d: path("M15.829 15.12a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 1 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

</style>
