<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i9Oa59s)" transform="rotate(-27.486 8.001 7.281)" class="tgn41ob8m"/><path fill="url(#iMXmxnb)" transform="rotate(-27.486 8.001 7.281)" class="tgn41ob8m"/><path fill="url(#iQT8YKc)" transform="rotate(-27.486 8.001 7.281)" class="tgn41ob8m"/><path fill="url(#ir2X6Mc)" transform="rotate(-27.486 8.001 7.281)" class="tgn41ob8m"/><path fill="url(#iZP7Azb)" transform="scale(-1 1)rotate(-27.486 2.593 53.907)" class="pnmas4b0d"/><path fill="url(#iKvJh5W)" transform="scale(-1 1)rotate(-27.486 2.593 53.907)" class="pnmas4b0d"/><path fill="url(#iyDDmMZ)" transform="scale(-1 1)rotate(-27.486 2.593 53.907)" class="pnmas4b0d"/><path fill="url(#iLWRW9Q)" transform="scale(-1 1)rotate(-27.486 2.593 53.907)" class="pnmas4b0d"/><g filter="url(#iss7z1c)"><path fill="url(#ihZG6Jm)" class="gs-0m1buq"/><path fill="url(#i40SKsb)" class="gs-0m1buq"/><path fill="url(#iDesTYb)" class="gs-0m1buq"/><path fill="url(#iUjMphb)" class="gs-0m1buq"/></g><g filter="url(#i7UpTZb)"><rect fill="url(#ivA0Vir)" class="nlrqaab3e"/><rect fill="url(#idzUIsy)" class="nlrqaab3e"/></g><g filter="url(#inYzC5b)"><path stroke="url(#iGReNWc)" class="i9_fs95dt"/></g><path fill="url(#ib6NDtc)" class="t4n0qxb2c"/><path fill="url(#iKjRv7c)" class="t4n0qxb2c"/><path fill="url(#iplGLUc)" class="b8u95wi1t"/><path fill="url(#inM8uTc)" class="b8u95wi1t"/><path fill="url(#i8hkIsd)" class="trfu4pbeh"/><path fill="url(#icwN9QU)" class="trfu4pbeh"/><path fill="url(#iAYk2hG)" class="q9nu6_iof"/><path fill="url(#iTTphZd)" class="q9nu6_iof"/><circle fill="url(#ioubDmb)" class="u9fkh2byq"/><circle fill="url(#ifJDmrH)" class="u9fkh2byq"/><path fill="url(#icoRg1d)" class="ov_wmzb1y"/><path fill="url(#iUh7xJe)" class="ov_wmzb1y"/><path fill="url(#i0Bjrye)" class="wtdb_48ie"/><path fill="url(#iHB8Zme)" class="wtdb_48ie"/><path fill="url(#i1z4d7d)" class="j6eelj-cv"/><path fill="url(#iUaj0Iu)" class="j6eelj-cv"/><path fill="url(#iBWONtz)" class="a0ppcjbin"/><path fill="url(#iNQNZPb)" class="a0ppcjbin"/><circle fill="url(#ioBrRPd)" transform="matrix(-1 0 0 1 21.67 7.43)" class="e4y-1lbum"/><circle fill="url(#i5G2Nwe)" transform="matrix(-1 0 0 1 21.67 7.43)" class="e4y-1lbum"/><g filter="url(#i9kWDCc)"><path fill="url(#iYDz60d)" class="xixpplsjf"/><path fill="url(#ior0qiP)" class="xixpplsjf"/><path fill="url(#ikLyW3c)" class="xixpplsjf"/></g><g filter="url(#iTrAaZb)"><path fill="url(#i6nyDvb)" class="bha09e2hy"/><path fill="url(#i4Y833b)" class="bha09e2hy"/><path fill="url(#iOAi2Gb)" class="bha09e2hy"/></g><g filter="url(#iLfTXDy)"><path fill="url(#iHgqQcb)" class="c18f10bbf"/><path fill="url(#ibZVmYu)" class="c18f10bbf"/></g><g filter="url(#igl1Ege)"><path fill="url(#ic4ZWcc)" class="qcc4p39df"/><path fill="url(#im7YRmd)" class="qcc4p39df"/><path fill="url(#iOhhXUd)" class="qcc4p39df"/></g><g filter="url(#iyUqRBc)"><path fill="url(#ilcA3Lc)" class="k5nqiacts"/><path fill="url(#ivIZWkd)" class="k5nqiacts"/></g><g filter="url(#iBMU6nb)"><path fill="url(#iWW3rpe)" class="d9k32s-zx"/></g><g filter="url(#if6l1He)"><path fill="url(#izDIdZd)" class="djpjdcbze"/><path fill="url(#iQLSjUd)" class="djpjdcbze"/></g><g filter="url(#iht5V4b)"><path fill="url(#iaiW25O)" class="dpuv5mb3h"/></g><g filter="url(#i4qxPpb)"><path fill="url(#ixkqPtd)" class="ikq19wppa"/></g><g filter="url(#iNZvj8b)"><path fill="url(#i5LO8bc)" class="w1iau6-cb"/><path fill="url(#iQFlPgc)" class="w1iau6-cb"/></g><g filter="url(#iDXLO1l)"><path fill="url(#ik8ZpdN)" class="qaemv3w1f"/></g><g filter="url(#iXZ4vuX)"><circle fill="url(#ieyHw2m)" class="kwh4844jo"/></g><circle fill="url(#iR3ZJ0d)" class="kwh4844jo"/><g filter="url(#ixdhmte)"><circle fill="url(#i6b3yha)" class="a9xosdb4w"/></g><g filter="url(#iHJiD3c)"><circle fill="url(#iPVztbc)" class="sit1spz0p"/><circle fill="url(#i9PZ6Lc)" class="sit1spz0p"/></g><g filter="url(#ic3lKpe)"><circle class="bxzblfb5l"/><circle fill="url(#i1sdjxb)" class="s27zctbzh"/><circle fill="url(#iwL5D0c)" class="s27zctbzh"/></g><path fill="url(#i6nqkId)" class="at3y6__el"/><path fill="url(#i0olppe)" class="at3y6__el"/><path fill="url(#i0vB7pc)" class="at3y6__el"/><path fill="url(#iMBnhub)" class="wvzuc6fsu"/><path fill="url(#igRQYab)" class="wvzuc6fsu"/><path fill="url(#iRLSCnd)" class="wvzuc6fsu"/><g filter="url(#isheRfe)"><path fill="url(#ifLLQub)" class="s-z6p3bgl"/></g><g filter="url(#i5k5uId)"><path class="qm9uxdomt"/><path fill="url(#iTOHQ4b)" class="g1vb-hznk"/><path fill="url(#i8z5i4c)" class="g1vb-hznk"/><path fill="url(#iZujJOr)" class="g1vb-hznk"/><path fill="url(#iKTYr5d)" class="g1vb-hznk"/></g><g filter="url(#izcU7fd)"><path class="renxz1sqz"/></g><g filter="url(#iail8mc)"><path class="xj4hy7q7a"/><path fill="url(#ifwU6Ac)" class="r_4101qrg"/><path fill="url(#iCC9A1c)" class="r_4101qrg"/><path fill="url(#iG3jS5c)" class="r_4101qrg"/><path fill="url(#iDs6NXc)" class="r_4101qrg"/></g><path stroke="url(#ip7QeKc)" class="du5alit4w"/><path class="kh6wsyajp"/><path fill="url(#iFQeGZc)" class="b1ozebbxm"/><path class="lev0xobhw"/><g filter="url(#iiwM4Qd)"><path class="m1kc--c8w"/><path fill="url(#i2odQcs)" class="crthazbcu"/></g><g filter="url(#iZwiwkc)"><path fill="url(#iDIBmCd)" class="nhvmh8srw"/></g><path class="di7qewbgm"/><path fill="url(#iqvHfqr)" class="vds5s6brs"/><path class="lo7olob5x"/><g filter="url(#ixIJUJF)"><path fill="url(#iCbzKob)" class="a7s84sb8x"/></g><g filter="url(#ipsKgjd)"><ellipse transform="rotate(-27.914 15.063 13.37)" class="e7vmqsekh"/><ellipse fill="url(#iT4Dbyu)" transform="rotate(-27.914 15.063 13.37)" class="r1xvh34oc"/></g><g filter="url(#ikDLM4b)"><path class="revjxkb3y"/><path fill="url(#i1d8scb)" class="v1fjeebax"/></g><g filter="url(#ilqGWCb)"><path stroke="url(#i3nE27d)" class="l48907-bb"/></g><g filter="url(#iv7laTb)"><path class="w23f8mb5e"/><path fill="url(#iltT3Vd)" class="xnjybqu-h"/></g><g filter="url(#i7YqIAb)"><path stroke="url(#isSSoqU)" class="zfm0l6d1q"/></g><g filter="url(#i8cjHlc)"><path stroke="url(#ibavnKd)" class="ewjirs5kt"/></g><defs><radialGradient id="i9Oa59s" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.636 10.72)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="vs6a_gbje"/><stop offset="1" class="p05v01y6n"/></radialGradient><radialGradient id="iQT8YKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 10.306 8.2)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="he0s_zrqe"/><stop offset="1" class="ngc6h6bst"/></radialGradient><radialGradient id="ir2X6Mc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.502 7.043)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="q7pd18pxe"/><stop offset="1" class="ervi6uxri"/></radialGradient><radialGradient id="iZP7Azb" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.997 3.08)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="vs6a_gbje"/><stop offset="1" class="p05v01y6n"/></radialGradient><radialGradient id="iyDDmMZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 2.305 .918)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="he0s_zrqe"/><stop offset="1" class="ngc6h6bst"/></radialGradient><radialGradient id="iLWRW9Q" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="q7pd18pxe"/><stop offset="1" class="ervi6uxri"/></radialGradient><radialGradient id="ihZG6Jm" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.647 22.375)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="iUjMphb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 18.21 22.375)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="ivA0Vir" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 18.053 6.125)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="idzUIsy" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 9.233 6.704)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="ib6NDtc" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 4.12 3.293)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="gbg_o2brc"/><stop offset="1" class="ojtd-2bym"/></radialGradient><radialGradient id="iKjRv7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.2132 .05173 -.03984 -.16419 8.354 6.712)" gradientUnits="userSpaceOnUse"><stop class="rinxg7b3w"/><stop offset="1" class="mr-9ywwkm"/></radialGradient><radialGradient id="iplGLUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 9.135 6.305)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="gbg_o2brc"/><stop offset="1" class="ojtd-2bym"/></radialGradient><radialGradient id="inM8uTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2259 .05875 -.04809 -.18493 9.049 6.743)" gradientUnits="userSpaceOnUse"><stop class="rinxg7b3w"/><stop offset="1" class="mr-9ywwkm"/></radialGradient><radialGradient id="i8hkIsd" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.16 3.34)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="gbg_o2brc"/><stop offset="1" class="ojtd-2bym"/></radialGradient><radialGradient id="icwN9QU" cx="0" cy="0" r="1" gradientTransform="matrix(-.21457 .05712 -.04771 -.17925 10.45 6.75)" gradientUnits="userSpaceOnUse"><stop class="rinxg7b3w"/><stop offset="1" class="mr-9ywwkm"/></radialGradient><radialGradient id="iAYk2hG" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.816 3.336)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="gbg_o2brc"/><stop offset="1" class="ojtd-2bym"/></radialGradient><radialGradient id="iTTphZd" cx="0" cy="0" r="1" gradientTransform="matrix(-.22656 .06252 -.05386 -.19519 9.768 6.791)" gradientUnits="userSpaceOnUse"><stop class="rinxg7b3w"/><stop offset="1" class="mr-9ywwkm"/></radialGradient><radialGradient id="ioubDmb" cx="0" cy="0" r="1" gradientTransform="rotate(134.624 4.003 5.996)scale(.6044)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="rg-2sfb_z"/><stop offset=".91" class="ta8v8mbic"/></radialGradient><radialGradient id="ifJDmrH" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .21094 -.20725 -.17654 11.098 7.28)" gradientUnits="userSpaceOnUse"><stop class="p_9wr0blz"/><stop offset="1" class="qjh6wtbsx"/></radialGradient><radialGradient id="icoRg1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.66762 0 0 -1.09544 24.49 6.327)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="sbdyv6jmf"/><stop offset="1" class="tnhyi-bom"/></radialGradient><radialGradient id="iUh7xJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.10128 .19105 -.1686 -.08938 24.46 6.6)" gradientUnits="userSpaceOnUse"><stop class="gflnmoosd"/><stop offset="1" class="j9d96zbhu"/></radialGradient><radialGradient id="i0Bjrye" cx="0" cy="0" r="1" gradientTransform="matrix(-.70736 0 0 -1.24403 23.814 6.305)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="sbdyv6jmf"/><stop offset="1" class="tnhyi-bom"/></radialGradient><radialGradient id="iHB8Zme" cx="0" cy="0" r="1" gradientTransform="rotate(116.317 9.836 10.693)scale(.24205 .20513)" gradientUnits="userSpaceOnUse"><stop class="gflnmoosd"/><stop offset="1" class="j9d96zbhu"/></radialGradient><radialGradient id="i1z4d7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 0 0 -1.20947 22.395 6.325)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="sbdyv6jmf"/><stop offset="1" class="tnhyi-bom"/></radialGradient><radialGradient id="iUaj0Iu" cx="0" cy="0" r="1" gradientTransform="matrix(-.10193 .21094 -.17622 -.08515 22.364 6.628)" gradientUnits="userSpaceOnUse"><stop class="gflnmoosd"/><stop offset="1" class="j9d96zbhu"/></radialGradient><radialGradient id="iBWONtz" cx="0" cy="0" r="1" gradientTransform="matrix(-.70944 0 0 -1.32351 23.097 6.327)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="sbdyv6jmf"/><stop offset="1" class="tnhyi-bom"/></radialGradient><radialGradient id="iNQNZPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10762 .23083 -.18853 -.0879 23.064 6.658)" gradientUnits="userSpaceOnUse"><stop class="gflnmoosd"/><stop offset="1" class="j9d96zbhu"/></radialGradient><radialGradient id="ioBrRPd" cx="0" cy="0" r="1" gradientTransform="rotate(127.213 .238 .266)scale(.65236)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="rg-2sfb_z"/><stop offset=".91" class="ta8v8mbic"/></radialGradient><radialGradient id="i5G2Nwe" cx="0" cy="0" r="1" gradientTransform="rotate(124.323 .276 .232)scale(.31867 .23988)" gradientUnits="userSpaceOnUse"><stop class="p_9wr0blz"/><stop offset="1" class="qjh6wtbsx"/></radialGradient><radialGradient id="iYDz60d" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.584 19.188)" gradientUnits="userSpaceOnUse"><stop class="cnpza7b-j"/><stop offset="1" class="qcugcqlkb"/></radialGradient><radialGradient id="ior0qiP" cx="0" cy="0" r="1" gradientTransform="rotate(111.28 2.852 12.756)scale(2.73303 3.08168)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="my3wtvo7r"/><stop offset="1" class="yi8xsxb7e"/></radialGradient><radialGradient id="ikLyW3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 20.097 21.686)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="xjez76bam"/><stop offset="1" class="fc_42m6ea"/></radialGradient><radialGradient id="i6nyDvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.772 6.918)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iHgqQcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.565 6.918)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="ic4ZWcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.346 6.918)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="im7YRmd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 3.045 7.313)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="ilcA3Lc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.71 6.918)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="ivIZWkd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.46 7.313)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="iQLSjUd" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.2 12.377)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iaiW25O" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.678 28.422)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="iQFlPgc" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.763 15.596)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="ik8ZpdN" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.99 28.97)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="ieyHw2m" cx="0" cy="0" r="1" gradientTransform="matrix(.84282 0 0 1.47494 13.16 13.444)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iR3ZJ0d" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 10.69 3.488)scale(.7957)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="i9PZ6Lc" cx="0" cy="0" r="1" gradientTransform="matrix(.39705 -.28911 .32998 .45318 18.71 13.317)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="i1sdjxb" cx="0" cy="0" r="1" gradientTransform="matrix(.39443 -.72547 .42462 .23086 18.51 13.838)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iwL5D0c" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -7.08 29.253)scale(.17522 .22588)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="i0olppe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.62776 .77263 0 17.369 12.833)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="i0vB7pc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.65995 .8207 0 15.18 12.898)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iRLSCnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.99995 -4.95769 0 16.18 12.707)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="dcym8repk"/><stop offset=".884" class="fkee40m0y"/><stop offset="1" class="an_-aznlj"/></radialGradient><radialGradient id="iTOHQ4b" cx="0" cy="0" r="1" gradientTransform="matrix(.38317 -1.41999 .52658 .1421 18.329 11.472)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="i8z5i4c" cx="0" cy="0" r="1" gradientTransform="matrix(1.83698 .16905 -.0909 .98773 17.54 10.627)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iZujJOr" cx="0" cy="0" r="1" gradientTransform="matrix(0 .80647 -1.24899 0 16.242 9.313)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iKTYr5d" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 25.808 -13.794)scale(1.83033 2.86752)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iDs6NXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .09457 -.30382 0 16.4 14.415)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iFQeGZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38957 -.61965 0 17.288 13.417)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i2odQcs" cx="0" cy="0" r="1" gradientTransform="matrix(-.11136 -.1435 .19757 -.15331 17.179 13.457)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqvHfqr" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38959 -.61968 0 15.193 13.416)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iT4Dbyu" cx="0" cy="0" r="1" gradientTransform="matrix(-.00371 -.23724 .28518 -.00446 15.056 13.522)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1d8scb" cx="0" cy="0" r="1" gradientTransform="matrix(-.09133 -.27948 .82682 -.27018 17.497 12.73)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iltT3Vd" cx="0" cy="0" r="1" gradientTransform="rotate(-71.904 16.269 -3.967)scale(.29402 .86986)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><filter id="iss7z1c" width="9.5" height="4.284" x="11.444" y="22.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="i7UpTZb" width="27.875" height="1.225" x="2.334" y="6.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="inYzC5b" width="27.781" height=".75" x="2.295" y="6.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".125"/></filter><filter id="i9kWDCc" width="10.708" height="10.353" x="11.075" y="12.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.490196 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="iTrAaZb" width="1.93" height="8.989" x="5.311" y="2.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="iLfTXDy" width="1.93" height="8.989" x="25.264" y="2.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="igl1Ege" width="1.93" height="5.973" x="3.381" y="3.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="iyUqRBc" width="1.93" height="5.973" x="27.194" y="3.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="iBMU6nb" width="3.719" height="6.065" x="9.162" y="23.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.4 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.435294 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23316" result="effect2_innerShadow_3987_23316"/></filter><filter id="if6l1He" width="4.477" height="4.023" x="8.787" y="19.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="iht5V4b" width="4.833" height="2.114" x="7.311" y="28.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="i4qxPpb" width="3.719" height="5.564" x="20.194" y="23.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.572549 0 0 0 0 0.4 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.435294 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23316" result="effect2_innerShadow_3987_23316"/></filter><filter id="iNZvj8b" width="4.477" height="4.023" x="19.811" y="19.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="iDXLO1l" width="4.833" height="2.114" x="20.431" y="28.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="iXZ4vuX" width="1.804" height="1.604" x="13.16" y="12.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="ixdhmte" width="1.956" height="1.956" x="12.984" y="12.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".25"/></filter><filter id="iHJiD3c" width="1.854" height="1.854" x="17.729" y="12.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="ic3lKpe" width="1.956" height="1.956" x="17.553" y="12.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".25"/></filter><filter id="isheRfe" width="4.039" height="3.473" x="15.323" y="9.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".5"/></filter><filter id="i5k5uId" width="6.052" height="4.063" x="13.216" y="9.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="izcU7fd" width="2.345" height="2.788" x="14.954" y="12.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".375"/></filter><filter id="iail8mc" width="1.101" height="1.488" x="15.691" y="13.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".05"/></filter><filter id="iiwM4Qd" width=".382" height=".338" x="16.934" y="13.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".025"/></filter><filter id="iZwiwkc" width=".336" height=".347" x="17.385" y="13.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".025"/></filter><filter id="ixIJUJF" width=".382" height=".407" x="15.252" y="13.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".025"/></filter><filter id="ipsKgjd" width=".442" height=".342" x="14.841" y="13.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".025"/></filter><filter id="ikDLM4b" width="1.553" height="1.137" x="16.797" y="11.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="ilqGWCb" width="1.324" height=".709" x="16.765" y="12.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".075"/></filter><filter id="iv7laTb" width="1.553" height="1.137" x="14.384" y="11.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23316"/></filter><filter id="i7YqIAb" width="1.324" height=".709" x="14.394" y="12.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".075"/></filter><filter id="i8cjHlc" width=".874" height="1.48" x="13.566" y="10.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23316" stdDeviation=".125"/></filter><linearGradient id="iMXmxnb" x1="7.43" x2="8.551" y1="8.38" y2="8.526" gradientUnits="userSpaceOnUse"><stop offset=".136" class="nx3rm_63e"/><stop offset="1" class="gem_9mbst"/></linearGradient><linearGradient id="iKvJh5W" x1="-.572" x2=".549" y1="1.099" y2="1.245" gradientUnits="userSpaceOnUse"><stop offset=".136" class="nx3rm_63e"/><stop offset="1" class="gem_9mbst"/></linearGradient><linearGradient id="i40SKsb" x1="20.584" x2="18.053" y1="25.688" y2="25.25" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="iDesTYb" x1="11.897" x2="14.709" y1="25.782" y2="24.688" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="iGReNWc" x1="2.67" x2="30.139" y1="7.836" y2="7.836" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="i4Y833b" x1="5.311" x2="6.803" y1="7.907" y2="7.907" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iOAi2Gb" x1="5.311" x2="5.584" y1="7.778" y2="7.778" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="ibZVmYu" x1="25.264" x2="26.459" y1="6.918" y2="6.918" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iOhhXUd" x1="3.229" x2="3.723" y1="6.918" y2="6.918" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="iWW3rpe" x1="8.617" x2="11.554" y1="25.84" y2="25.84" gradientUnits="userSpaceOnUse"><stop offset=".335" class="pkg_5ym1q"/><stop offset="1" class="b0jqb_u5u"/></linearGradient><linearGradient id="izDIdZd" x1="12.764" x2="8.787" y1="22.204" y2="22.204" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="ixkqPtd" x1="23.958" x2="21.02" y1="25.636" y2="25.636" gradientUnits="userSpaceOnUse"><stop offset=".335" class="pkg_5ym1q"/><stop offset="1" class="b0jqb_u5u"/></linearGradient><linearGradient id="i5LO8bc" x1="19.811" x2="23.787" y1="22.204" y2="22.204" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="i6b3yha" x1="13.962" x2="13.654" y1="13.578" y2="13.578" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iPVztbc" x1="19.052" x2="18.659" y1="12.92" y2="14.138" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="i6nqkId" x1="18.18" x2="14.512" y1="13.631" y2="14.178" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iMBnhub" x1="13.65" x2="14.554" y1="14.926" y2="14.894" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="igRQYab" x1="18.605" x2="18.071" y1="14.522" y2="14.475" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="ifLLQub" x1="15.987" x2="19.898" y1="12.197" y2="10.797" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="ifwU6Ac" x1="15.827" x2="16.277" y1="14.147" y2="14.147" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iCC9A1c" x1="16.693" x2="16.2" y1="14.302" y2="14.295" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iG3jS5c" x1="16.335" x2="16.335" y1="14.658" y2="14.383" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="ip7QeKc" x1="15.744" x2="15.953" y1="15.455" y2="15.125" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iDIBmCd" x1="17.662" x2="17.511" y1="13.442" y2="13.535" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCbzKob" x1="15.55" x2="15.399" y1="13.442" y2="13.535" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3nE27d" x1="17.569" x2="17.197" y1="12.32" y2="12.05" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="isSSoqU" x1="14.915" x2="15.287" y1="12.32" y2="12.05" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="ibavnKd" x1="14.003" x2="14.003" y1="11.086" y2="12.122" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-lifting-weights-medium" /></template>
<style>
.a0ppcjbin {
  d: path("M23.38 6.018a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.016z");
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a7s84sb8x {
  d: path("M15.584 13.566c0-.139-.113-.231-.143-.26l-.139.135l.085.173z");
}

.a9xosdb4w {
  cx: 13.962px;
  cy: 13.444px;
  r: 0.478px;
}

.an_-aznlj {
  stop-color: var(--svg-color--7c5267, #7C5267);
}

.at3y6__el {
  d: path("M13.793 13.15h.023s-.026-.41-.051-.691c0-.128.051-.282.154-.359l.077-.077a.5.5 0 0 0 .18-.41v-.41a.25.25 0 0 1 .207-.255c.31-.077.953-.205 1.88-.205c.928 0 1.572.128 1.881.205a.28.28 0 0 1 .206.256v.41c0 .153.077.307.18.41c.242.168.227.261.207.46c-.026.257-.052.692-.052.692h.009l-.128 1.901c-.077.85-.745 1.442-1.542 1.442h-1.542c-.822 0-1.464-.592-1.541-1.442z");
}

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.b0jqb_u5u {
  stop-color: var(--svg-color--bc9480, #BC9480);
}

.b1ozebbxm {
  d: path("M17.29 13.188a.43.43 0 0 1 .412.541h-.828a.43.43 0 0 1 .415-.541");
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.b8u95wi1t {
  d: path("M8.432 6.057a.422.422 0 1 1 .844-.033v.585a.4.4 0 0 1-.799.03z");
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bha09e2hy {
  d: path("M5.31 3.324a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bxzblfb5l {
  cx: 18.531px;
  cy: 13.444px;
  r: 0.478px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c18f10bbf {
  d: path("M27.194 3.324a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnpza7b-j {
  stop-color: var(--svg-color--4baeff, #4BAEFF);
}

.crthazbcu {
  d: path("M17.258 13.278c.03.04-.033.09-.106.145c-.072.054-.126.092-.157.052c-.03-.041.004-.118.076-.173c.073-.054.156-.065.187-.024");
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d9k32s-zx {
  d: path("m9.675 29.308l-.513-5.893h3.22l-.534 5.965z");
}

.dcym8repk {
  stop-color: var(--svg-color--9b7168, #9B7168);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.di7qewbgm {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.093 13.057a.67.67 0 0 0-.65.508a.132.132 0 0 0 .128.164h1.071a.11.11 0 0 0 .11-.13a.67.67 0 0 0-.66-.542");
}

.djpjdcbze {
  d: path("M8.787 21.497a1.988 1.988 0 1 1 3.977 0v1.685a.35.35 0 0 1-.35.35H9.137a.35.35 0 0 1-.35-.35z");
}

.dpuv5mb3h {
  d: path("M7.31 29.96v.376h4.634v-1.914H9.592c-.383.377-1.215.73-1.836.942c-.398.168-.445.442-.445.596");
}

.du5alit4w {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.6 14.965c.185.097.406.152.642.152c.238 0 .457-.055.642-.152a.124.124 0 0 1 .147.024a.12.12 0 0 1 .013.149m-1.444-.173l1.402.145m-1.402-.145a.12.12 0 0 0-.147.025a.116.116 0 0 0-.013.148m.16-.173l-.118.145m1.562.028l-.042-.028m.042.028l-.042-.028m.042.028a.96.96 0 0 1-.802.428a.96.96 0 0 1-.802-.428m1.562-.028a.91.91 0 0 1-.76.406a.91.91 0 0 1-.76-.406m-.042.028l.042-.028m-.042.028l.042-.028");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4y-1lbum {
  r: 0.398px;
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.e7vmqsekh {
  cx: 15.063px;
  cy: 13.371px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.187px;
  ry: 0.095px;
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ervi6uxri {
  stop-color: var(--svg-color--815440, #815440);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.ewjirs5kt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.065 11.133v.431c-.004.072-.034.231-.124.299");
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fc_42m6ea {
  stop-color: var(--svg-color--3a9cef, #3A9CEF);
  stop-opacity: 0;
}

.fkee40m0y {
  stop-color: var(--svg-color--8f5d78, #8F5D78);
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g1vb-hznk {
  d: path("m18.556 10.333l.206.102c.361.18.567.59.49 1.025l-.284 1.46c-.025.15-.124.252-.274.256h-.009s.026-.435.052-.691c.02-.208-.016-.272-.206-.462a.6.6 0 0 1-.18-.41v-.082a.28.28 0 0 0-.207-.256c-.309-.077-.953-.205-1.88-.205c-.928 0-1.572.128-1.881.205a.25.25 0 0 0-.206.256v.083a.5.5 0 0 1-.18.41l-.078.076c-.103.077-.154.23-.154.359c.025.282.051.691.051.691h-.023a.304.304 0 0 1-.286-.256l-.283-1.46a.98.98 0 0 1 .515-.999l.206-.102c.129-.077.258-.18.386-.282l.464-.487a.94.94 0 0 1 1.056-.153c.258.077.541.077.799 0a1.16 1.16 0 0 1 1.134.256l.386.384c.103.128.232.205.386.282");
}

.gbg_o2brc {
  stop-color: var(--svg-color--bf9b81, #BF9B81);
}

.gem_9mbst {
  stop-color: var(--svg-color--7f575c, #7F575C);
  stop-opacity: 0;
}

.gflnmoosd {
  stop-color: var(--svg-color--b09083, #B09083);
}

.gs-0m1buq {
  d: path("M16.272 26.36c-2.363 0-4.203-.719-4.828-1.078v-2.907h9.5v3.016c-.573.323-2.31.969-4.672.969");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.he0s_zrqe {
  stop-color: var(--svg-color--6d3e3a, #6D3E3A);
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
}

.i9_fs95dt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.67 6.836h27.031");
}

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.ikq19wppa {
  d: path("m22.94 28.879l.472-5.464h-3.218l.477 5.464z");
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.j6eelj-cv {
  d: path("M22.663 6.056a.401.401 0 1 0-.802-.014v.575a.391.391 0 0 0 .783.013z");
}

.j9d96zbhu {
  stop-color: var(--svg-color--b09083, #B09083);
  stop-opacity: 0;
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.k5nqiacts {
  d: path("M29.123 4.832a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.kh6wsyajp {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.389 13.057a.67.67 0 0 1 .65.508a.132.132 0 0 1-.128.164h-1.072a.11.11 0 0 1-.109-.13a.67.67 0 0 1 .659-.542");
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kwh4844jo {
  cx: 13.962px;
  cy: 13.444px;
  r: 0.802px;
}

.l097mcblv {
  stop-color: var(--svg-color--433f49, #433F49);
}

.l48907-bb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.99 12.574c.166-.13.526-.308.874-.247");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lev0xobhw {
  fill: var(--svg-color--000, #000);
  d: path("M17.044 13.616c0-.136.109-.245.245-.245a.244.244 0 0 1 .218.358h-.434a.2.2 0 0 1-.03-.113");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo7olob5x {
  fill: var(--svg-color--000, #000);
  d: path("M15.437 13.616a.244.244 0 0 0-.245-.245a.244.244 0 0 0-.218.358h.434a.24.24 0 0 0 .03-.113");
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.m1kc--c8w {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.258 13.278c.03.04-.033.09-.106.145c-.072.054-.126.092-.157.052c-.03-.041.004-.118.076-.173c.073-.054.156-.065.187-.024");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mr-9ywwkm {
  stop-color: var(--svg-color--c2a08d, #C2A08D);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.my3wtvo7r {
  stop-color: var(--svg-color--2161bb, #2161BB);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.ngc6h6bst {
  stop-color: var(--svg-color--8d625b, #8D625B);
  stop-opacity: 0;
}

.nhvmh8srw {
  d: path("M17.67 13.56a.4.4 0 0 0-.11-.223l-.125.137l.056.11z");
}

.nlrqaab3e {
  width: 27.875px;
  height: 1.025px;
  x: 2.334px;
  y: 6.405px;
  rx: 0.2px;
}

.nx3rm_63e {
  stop-color: var(--svg-color--59343e, #59343E);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.ojtd-2bym {
  stop-color: var(--svg-color--8f5c5f, #8F5C5F);
}

.ov_wmzb1y {
  d: path("M24.755 6.14a.399.399 0 1 0-.796-.034v.46a.38.38 0 0 0 .757.032z");
}

.p_9wr0blz {
  stop-color: var(--svg-color--ab8d80, #AB8D80);
}

.p05v01y6n {
  stop-color: var(--svg-color--9c6e68, #9C6E68);
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pkg_5ym1q {
  stop-color: var(--svg-color--c4958a, #C4958A);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.pty90zojz {
  stop-color: var(--svg-color--7b7784, #7B7784);
}

.q-vr2ac-v {
  stop-color: var(--svg-color--5c447a, #5C447A);
}

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.q7pd18pxe {
  stop-color: var(--svg-color--815440, #815440);
}

.q9nu6_iof {
  d: path("M9.147 6.018a.424.424 0 1 1 .847-.016v.661a.411.411 0 0 1-.822.016z");
}

.qaemv3w1f {
  d: path("M25.264 29.96v.376H20.63v-1.914h2.352c.383.377 1.215.73 1.836.942c.398.168.445.442.445.596");
}

.qcc4p39df {
  d: path("M3.381 4.832a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.qcugcqlkb {
  stop-color: var(--svg-color--2e82d2, #2E82D2);
}

.qjh6wtbsx {
  stop-color: var(--svg-color--ab8d80, #AB8D80);
  stop-opacity: 0;
}

.qm9uxdomt {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m18.556 10.333l.206.102c.361.18.567.59.49 1.025l-.284 1.46c-.025.15-.124.252-.274.256h-.009s.026-.435.052-.691c.02-.208-.016-.272-.206-.462a.6.6 0 0 1-.18-.41v-.082a.28.28 0 0 0-.207-.256c-.309-.077-.953-.205-1.88-.205c-.928 0-1.572.128-1.881.205a.25.25 0 0 0-.206.256v.083a.5.5 0 0 1-.18.41l-.078.076c-.103.077-.154.23-.154.359c.025.282.051.691.051.691h-.023a.304.304 0 0 1-.286-.256l-.283-1.46a.98.98 0 0 1 .515-.999l.206-.102c.129-.077.258-.18.386-.282l.464-.487a.94.94 0 0 1 1.056-.153c.258.077.541.077.799 0a1.16 1.16 0 0 1 1.134.256l.386.384c.103.128.232.205.386.282");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r_4101qrg {
  d: path("m16.058 13.506l-.255.816a.26.26 0 0 0 .25.336h.378a.26.26 0 0 0 .25-.335l-.256-.817c-.054-.18-.31-.18-.367 0");
}

.r1xvh34oc {
  cx: 15.063px;
  cy: 13.371px;
  rx: 0.187px;
  ry: 0.095px;
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.renxz1sqz {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m16.11 13.585l-.394.816c-.05.168.068.336.234.336h.354c.166 0 .283-.17.234-.336l-.239-.816c-.051-.181-.136-.181-.19 0");
}

.revjxkb3y {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M17.896 12.172h-.004l-.008-.002a1 1 0 0 0-.09-.01a1.36 1.36 0 0 0-.895.273a.256.256 0 1 0 .308.41a.85.85 0 0 1 .55-.172l.032.003h.004a.256.256 0 0 0 .103-.502");
}

.rg-2sfb_z {
  stop-color: var(--svg-color--957562, #957562);
}

.rinxg7b3w {
  stop-color: var(--svg-color--c2a08d, #C2A08D);
}

.s-z6p3bgl {
  d: path("m18.146 10.743l-1.479.492a.503.503 0 0 0 .226.976l1.47-.197z");
}

.s27zctbzh {
  cx: 18.531px;
  cy: 13.444px;
  r: 0.478px;
}

.sbdyv6jmf {
  stop-color: var(--svg-color--a6876e, #A6876E);
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.sit1spz0p {
  cx: 18.531px;
  cy: 13.444px;
  r: 0.802px;
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t4n0qxb2c {
  d: path("M7.773 6.14a.399.399 0 1 1 .796-.034v.46a.38.38 0 0 1-.758.032z");
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.ta8v8mbic {
  stop-color: var(--svg-color--97696d, #97696D);
}

.tgn41ob8m {
  d: path("M8.001 7.281h2.46v7.269h-2.46z");
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tnhyi-bom {
  stop-color: var(--svg-color--8f5d62, #8F5D62);
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.trfu4pbeh {
  d: path("M9.864 6.056a.401.401 0 1 1 .802-.014v.575a.391.391 0 0 1-.782.013z");
}

.ty2qe1a3m {
  stop-color: var(--svg-color--97959c, #97959C);
}

.u-rrnxf4y {
  stop-color: var(--svg-color--51435f, #51435F);
  stop-opacity: 0;
}

.u9fkh2byq {
  cx: 10.858px;
  cy: 7.43px;
  r: 0.398px;
}

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.up_0b0b8w {
  stop-color: var(--svg-color--8d8c90, #8D8C90);
}

.utuf8geyx {
  stop-color: var(--svg-color--cabed2, #CABED2);
  stop-opacity: 0;
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1fjeebax {
  d: path("M17.896 12.172h-.004l-.008-.002a1 1 0 0 0-.09-.01a1.36 1.36 0 0 0-.895.273a.256.256 0 1 0 .308.41a.85.85 0 0 1 .55-.172l.032.003h.004a.256.256 0 0 0 .103-.502");
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.vds5s6brs {
  d: path("M15.192 13.188a.43.43 0 0 0-.413.541h.828a.432.432 0 0 0-.415-.541");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vs6a_gbje {
  stop-color: var(--svg-color--c69e8a, #C69E8A);
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w1iau6-cb {
  d: path("M23.787 21.497a1.988 1.988 0 0 0-3.976 0v1.685c0 .193.157.35.35.35h3.276a.35.35 0 0 0 .35-.35z");
}

.w23f8mb5e {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M14.588 12.172h.004l.007-.002a1 1 0 0 1 .09-.01q.087-.01.226.004c.184.02.427.087.669.268a.256.256 0 1 1-.308.41a.85.85 0 0 0-.55-.171l-.03.003h-.006a.256.256 0 0 1-.102-.502");
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.wtdb_48ie {
  d: path("M24.095 6.057a.422.422 0 1 0-.843-.033v.585a.4.4 0 0 0 .798.03z");
}

.wvzuc6fsu {
  d: path("M13.765 12.459c0-.128.051-.282.154-.359l.077-.077a.5.5 0 0 0 .18-.41v-.41a.25.25 0 0 1 .207-.255c.31-.077.953-.205 1.88-.205c.928 0 1.572.128 1.881.205a.28.28 0 0 1 .206.256v.41c0 .153.077.307.18.41c.242.168.227.261.207.46c-.026.257-.052.692-.052.692h.009l-.128 1.901c-.077.85-.745 1.442-1.542 1.442h-1.542c-.822 0-1.464-.592-1.541-1.442c-.067-.872-.097-1.747-.176-2.618");
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xixpplsjf {
  d: path("m11.22 13.456l2.396-1.12l2.578 3.399l2.468-3.563l2.73 1.318a.25.25 0 0 1 .113.34l-1.194 2.304a1 1 0 0 0-.112.48l.12 5.761h-7.985v-5.787a1 1 0 0 0-.098-.433L11.1 13.79a.25.25 0 0 1 .12-.335");
}

.xj4hy7q7a {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m16.058 13.506l-.255.816a.26.26 0 0 0 .25.336h.378a.26.26 0 0 0 .25-.335l-.256-.817c-.054-.18-.31-.18-.367 0");
}

.xjez76bam {
  stop-color: var(--svg-color--1071cb, #1071CB);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xnjybqu-h {
  d: path("M14.588 12.172h.004l.007-.002a1 1 0 0 1 .09-.01q.087-.01.226.004c.184.02.427.087.669.268a.256.256 0 1 1-.308.41a.85.85 0 0 0-.55-.171l-.03.003h-.006a.256.256 0 0 1-.102-.502");
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.yi8xsxb7e {
  stop-color: var(--svg-color--3770bc, #3770BC);
  stop-opacity: 0;
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

.zfm0l6d1q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.494 12.574c-.166-.13-.527-.308-.875-.247");
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
