<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iomczdc)"><path fill="url(#ih9WEkc)" clip-rule="evenodd" class="qt7d8ab9i"/><path fill="url(#iPPzISc)" clip-rule="evenodd" class="qt7d8ab9i"/><path fill="url(#iRz3oxc)" clip-rule="evenodd" class="qt7d8ab9i"/><path fill="url(#iyjlTXF)" clip-rule="evenodd" class="qt7d8ab9i"/><path fill="url(#ilYxJie)" clip-rule="evenodd" class="qt7d8ab9i"/><path fill="url(#iqZGRjb)" clip-rule="evenodd" class="qt7d8ab9i"/><path fill="url(#iYI6cLc)" clip-rule="evenodd" class="qt7d8ab9i"/><path fill="url(#iX6IBSc)" clip-rule="evenodd" class="qt7d8ab9i"/><path fill="url(#iJVuujc)" clip-rule="evenodd" class="qt7d8ab9i"/><path fill="url(#iTYtGwe)" clip-rule="evenodd" class="qt7d8ab9i"/></g><path fill="url(#iOzDOpd)" class="cfg0tb7kn"/><path fill="url(#i0Wrsuc)" class="cfg0tb7kn"/><path fill="url(#iSlb66d)" class="cfg0tb7kn"/><path fill="url(#iNelxIO)" class="cfg0tb7kn"/><path fill="url(#iIql0HB)" class="cfg0tb7kn"/><path fill="url(#iJ33pUW)" class="cfg0tb7kn"/><path fill="url(#ibSLChQ)" class="cfg0tb7kn"/><path fill="url(#iNM475c)" class="d34q2nbhk"/><path fill="url(#iVxy4Jb)" class="v3kg3vvpv"/><path fill="url(#iZX2Lwe)" class="hiuialb7f"/><path fill="url(#iUqMend)" class="hiuialb7f"/><path fill="url(#i4QGmfn)" class="hiuialb7f"/><path fill="url(#id9aNiU)" class="d7t-w3bii"/><path fill="url(#io2euVc)" class="d7t-w3bii"/><path fill="url(#ijEVEDP)" class="d7t-w3bii"/><path fill="url(#ibrhWuc)" class="zm--4cwlh"/><path fill="url(#i16cMAc)" class="zm--4cwlh"/><path fill="url(#iNM475c)" class="d34q2nbhk"/><path fill="url(#iVxy4Jb)" class="v3kg3vvpv"/><g filter="url(#i4oHj4d)"><path class="hvnxgib9j"/></g><g filter="url(#iR3sAtb)"><path fill="url(#inKFfXb)" class="y_w8ygbcs"/></g><path fill="url(#iLlshQT)" class="c0x_nlp-j"/><path fill="url(#ifcr5ge)" class="c0x_nlp-j"/><path fill="url(#imqpEBe)" class="c0x_nlp-j"/><path fill="url(#iAuoTob)" class="c0x_nlp-j"/><path fill="url(#iFCFiSd)" class="c0x_nlp-j"/><path fill="url(#iu43b0b)" class="c0x_nlp-j"/><path fill="url(#iiWUDrd)" class="ygcxgdb6u"/><path fill="url(#iJyelRX)" class="ygcxgdb6u"/><path fill="url(#ifqomUc)" class="ygcxgdb6u"/><path fill="url(#iXKEaFb)" class="ygcxgdb6u"/><path fill="url(#ii2ihIc)" class="ygcxgdb6u"/><path fill="url(#i58vg4c)" class="ygcxgdb6u"/><path fill="url(#i3qSGeb)" class="gxfu6xbrp"/><path clip-rule="evenodd" class="q0omcobvq"/><path fill="url(#i0dvkGB)" clip-rule="evenodd" class="d71a5hb6m"/><path fill="url(#iXHx3Ec)" clip-rule="evenodd" class="d71a5hb6m"/><path fill="url(#it1aBQd)" clip-rule="evenodd" class="d71a5hb6m"/><path fill="url(#i0PdAEe)" clip-rule="evenodd" class="d71a5hb6m"/><g filter="url(#iAPgYab)"><path class="q_nmtdtfz"/></g><path fill="url(#iGwTmbZ)" class="do-bxqb6m"/><g filter="url(#iq2aT8p)"><path fill="url(#ihosLHc)" class="ieh-bmbmr"/></g><g filter="url(#iyeeIOz)"><path fill="url(#ij6BU3d)" clip-rule="evenodd" class="keav6qbwv"/></g><g filter="url(#i0Bhuob)"><path class="bl736eqew"/></g><path fill="url(#iHFDh4d)" clip-rule="evenodd" class="wqc_w2bup"/><path fill="url(#iHvAkEd)" clip-rule="evenodd" class="wqc_w2bup"/><path fill="url(#i4dS4is)" clip-rule="evenodd" class="ov9b4g-co"/><path fill="url(#iXSl1hc)" clip-rule="evenodd" class="ov9b4g-co"/><g filter="url(#iHYhqnd)"><path fill="url(#iPBYiEb)" class="e1blajbcf"/></g><g filter="url(#iguW2vb)"><path fill="url(#iGCV9fb)" class="fisbdwbzk"/><path fill="url(#iHiStAd)" class="fisbdwbzk"/></g><g filter="url(#i9MChhd)"><path class="tnslzrbma"/><path fill="url(#iNMzDhd)" class="lvfx8kb6o"/></g><g filter="url(#inVJKwc)"><path class="vh23662ds"/><path fill="url(#ijIoUee)" class="pjct3_xqc"/></g><g filter="url(#icsUPqz)"><path fill="url(#iMWr0Ac)" class="k_rid7bmg"/><path fill="url(#id8QYgc)" class="k_rid7bmg"/><path fill="url(#iyY4Zfe)" class="k_rid7bmg"/><path fill="url(#iLfXANb)" class="k_rid7bmg"/><path fill="url(#iGREQHb)" class="k_rid7bmg"/><path fill="url(#iHq0mHd)" class="k_rid7bmg"/><path fill="url(#i9icMwc)" class="k_rid7bmg"/></g><path fill="url(#iEbccNb)" class="j9x2zdbja"/><path fill="url(#ivW0mZd)" class="j9x2zdbja"/><g filter="url(#iQ0Jkyb)"><path class="m48yk268l"/></g><g filter="url(#ita3sod)"><path class="k34g2lbpi"/><path fill="url(#ijTapAd)" class="s9u9atb0s"/><path fill="url(#iDJnC2M)" class="s9u9atb0s"/><path fill="url(#iRl65Wc)" class="s9u9atb0s"/></g><path fill="url(#ixvExfe)" class="s9u9atb0s"/><path fill="url(#ioFBjUN)" class="s9u9atb0s"/><path stroke="url(#iPGKBtb)" class="shno8vb_u"/><g filter="url(#i86HPXM)"><path class="t8pzkjb2s"/></g><g filter="url(#icqd3nb)"><path class="gbq2cubxr"/></g><g filter="url(#iVb8Znl)"><path class="g-038cbdt"/></g><g filter="url(#iPpfcfc)"><path clip-rule="evenodd" class="aopy3pbzd"/></g><path class="y623nhl9a"/><path fill="url(#iX5736b)" class="skbyo7b7w"/><path class="o-3cwm4mc"/><g filter="url(#iqzZulb)"><path class="nd_b8e5hf"/><path fill="url(#iqPSzab)" class="c648-8dat"/></g><g filter="url(#iEZQY1b)"><path fill="url(#iDqJoyc)" class="qkd1vh4ud"/></g><path class="idrj4ac7u"/><path fill="url(#iwhklBb)" class="vbqduhb-c"/><path class="i62jx7m-s"/><g filter="url(#izBf7Fc)"><path fill="url(#iKkjpbc)" class="u-u60pbom"/></g><g filter="url(#iV3MzVd)"><ellipse transform="rotate(-27.914 13.547 10.007)" class="pew3kybpl"/><ellipse fill="url(#i3O1bpe)" transform="rotate(-27.914 13.547 10.007)" class="jbi-edbxv"/></g><g filter="url(#ixpfBCc)"><path class="mzjj6abkt"/></g><g filter="url(#iIRfHZb)"><path class="cjp7vbcdm"/></g><g filter="url(#iUoVcgb)"><path fill="url(#ilaOclc)" class="c4269f9-h"/><path fill="url(#irPUCOc)" class="c4269f9-h"/></g><g filter="url(#ijSr5kd)"><path fill="url(#iXuUj9b)" class="mu_doqb_t"/><path fill="url(#iz9BvXK)" class="mu_doqb_t"/><path fill="url(#icM5Z1J)" class="mu_doqb_t"/></g><g filter="url(#i16uEnd)"><path stroke="url(#i5tpw9c)" class="gndpcrt6r"/></g><defs><radialGradient id="iPPzISc" cx="0" cy="0" r="1" gradientTransform="matrix(1.74318 -3.62044 8.25485 3.97456 20.693 16.518)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iRz3oxc" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 3.226 11.691)scale(5.77873 5.40927)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iyjlTXF" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 4.133 8.942)scale(3.98975 4.91117)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="ilYxJie" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.738 8.362)scale(1.78101 1.61886)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iqZGRjb" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.365 4.07)scale(2.38706 3.50899)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iYI6cLc" cx="0" cy="0" r="1" gradientTransform="matrix(2.16229 3.16788 -5.52839 3.77349 12.162 3.127)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="iX6IBSc" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.66 7.205)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iJVuujc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.51 9.848)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iTYtGwe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15113 1.34089 -2.13644 -5.02072 23.241 12.63)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iOzDOpd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.195 24)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="iIql0HB" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.176 8.217)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="iJ33pUW" cx="0" cy="0" r="1" gradientTransform="rotate(77.152 -6.372 23.597)scale(3.65398 4.0429)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="ibSLChQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.966 30.07)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="iZX2Lwe" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.332 24.782)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="iUqMend" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.739 12.37)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="id9aNiU" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.231 22.032)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="io2euVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.544 20.407)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="ibrhWuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 16 18.626)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="laxsilb3j"/><stop offset="1" class="k5_wf-bwi"/></radialGradient><radialGradient id="i16cMAc" cx="0" cy="0" r="1" gradientTransform="scale(2.8605 6.53125)rotate(-90 5.2 -.52)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="p5_0bzbaz"/><stop offset="1" class="iqq-d2brk"/></radialGradient><radialGradient id="iAuoTob" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 19.139 18.188)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="iFCFiSd" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.447 26.63)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="iu43b0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.139 24.938)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="iiWUDrd" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.373 11.316)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="iJyelRX" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.13 24.993)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="iXKEaFb" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.302 19.563)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="ii2ihIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 12.098 18.392)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="i58vg4c" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -17.107 24.262)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="i3qSGeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.125 -2.67249 0 15.985 16.461)" gradientUnits="userSpaceOnUse"><stop class="bfpb1bcgi"/><stop offset=".47" class="lxiaxgu3j"/><stop offset=".858" class="a3iiymleb"/></radialGradient><radialGradient id="iXHx3Ec" cx="0" cy="0" r="1" gradientTransform="matrix(.5209 2.3152 -1.36598 .30734 18.128 16.134)" gradientUnits="userSpaceOnUse"><stop class="w_gx_6l5c"/><stop offset="1" class="sruu51y8f"/></radialGradient><radialGradient id="it1aBQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.582 20.11)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="i0PdAEe" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.795 12.23)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="fv5w29bdg"/><stop offset="1" class="e6fuuiw3e"/></radialGradient><radialGradient id="iGwTmbZ" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.134 18.101)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="ihosLHc" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.248 25.978)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="iHvAkEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.13 23.641)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="iGCV9fb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.04 11.14)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iHiStAd" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 21.062 8.918)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iNMzDhd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.847 -52.05)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="ijIoUee" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 11.334 10.7)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iMWr0Ac" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.86 10.162)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="id8QYgc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.9 10.86)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iyY4Zfe" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.82 16.945)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iLfXANb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.4375 -10.082 0 16 9.875)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sgt5sn5oc"/><stop offset="1" class="gxm-dc6uw"/></radialGradient><radialGradient id="iGREQHb" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.9 6.805)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iHq0mHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 18.301 9.744)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="i9icMwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.082 9.831)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iEbccNb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.096 11.231)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="ivW0mZd" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 13.5 4.656)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="ijTapAd" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.784 11.958)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="ioFBjUN" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.285 8.41)scale(1.57489 2.10944)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="iX5736b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 10.102)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iqPSzab" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.954 10.187)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwhklBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.818 10.102)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i3O1bpe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.847 -1.5)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ilaOclc" cx="0" cy="0" r="1" gradientTransform="matrix(1.93486 2.6818 -5.32876 3.84458 10.042 4.451)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="irPUCOc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87735 2.48068 -1.9455 -1.47233 13.285 4.686)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iXuUj9b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11195 4.39145 -6.24446 -3.00311 17.91 2.775)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iz9BvXK" cx="0" cy="0" r="1" gradientTransform="matrix(-.8568 3.20722 -5.72497 -1.5294 18.313 3.948)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="icM5Z1J" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.414 -.38)scale(7.21046 6.45439)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><linearGradient id="ih9WEkc" x1="20.693" x2="13.888" y1="3.747" y2="16.352" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="i0Wrsuc" x1="23.309" x2="22.997" y1="24.68" y2="24.68" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iSlb66d" x1="8.731" x2="9.067" y1="24.68" y2="24.68" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="iNelxIO" x1="16.176" x2="16.176" y1="31.032" y2="29.22" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iNM475c" x1="8.815" x2="23.191" y1="15.509" y2="15.509" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iVxy4Jb" x1="8.815" x2="23.191" y1="15.479" y2="15.479" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i4QGmfn" x1="6.995" x2="6.995" y1="30.845" y2="29.385" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="ijEVEDP" x1="22.666" x2="23.445" y1="25.718" y2="25.718" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="inKFfXb" x1="16.176" x2="23.801" y1="27.064" y2="19.47" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="iLlshQT" x1="21.89" x2="16.775" y1="18.459" y2="23.977" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="ifcr5ge" x1="20.044" x2="19.887" y1="15.74" y2="17.802" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="imqpEBe" x1="17.582" x2="18.739" y1="18.985" y2="19.47" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="ifqomUc" x1="12.27" x2="12.598" y1="23.282" y2="22.923" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="i0dvkGB" x1="20.309" x2="19.637" y1="23.751" y2="23.767" gradientUnits="userSpaceOnUse"><stop offset=".294" class="nrx5bzr9s"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="ij6BU3d" x1="12.205" x2="12.205" y1="19.949" y2="28.532" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="iHFDh4d" x1="9.514" x2="10.408" y1="25.348" y2="25.348" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="i4dS4is" x1="13.887" x2="14.559" y1="25.359" y2="25.359" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iXSl1hc" x1="14.95" x2="14.707" y1="24.876" y2="24.876" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="iPBYiEb" x1="9.705" x2="12.665" y1="10.787" y2="10.787" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iDJnC2M" x1="14.954" x2="15.808" y1="11.976" y2="12.08" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iRl65Wc" x1="16" x2="16" y1="12.83" y2="12.22" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="ixvExfe" x1="16.078" x2="16.078" y1="12.804" y2="12.664" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="iPGKBtb" x1="15.271" x2="15.724" y1="14.307" y2="13.435" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="iDqJoyc" x1="18.96" x2="18.646" y1="10.157" y2="10.35" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKkjpbc" x1="14.562" x2="14.248" y1="10.157" y2="10.35" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5tpw9c" x1="13.109" x2="13.653" y1="4.501" y2="5.775" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><filter id="iomczdc" width="15.268" height="15.768" x="8.491" y="1.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24154"/></filter><filter id="i4oHj4d" width="7.147" height="11.557" x="9.03" y="15.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".5"/></filter><filter id="iR3sAtb" width="7.147" height="11.557" x="15.924" y="15.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".5"/></filter><filter id="iAPgYab" width="3.699" height="3.699" x="16.995" y="24.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".375"/></filter><filter id="iq2aT8p" width="1.42" height="1.42" x="18.965" y="24.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24154"/></filter><filter id="iyeeIOz" width="5.381" height="7.171" x="9.514" y="19.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24154"/></filter><filter id="i0Bhuob" width="5.3" height="6.89" x="9.58" y="19.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".15"/></filter><filter id="iHYhqnd" width="3.368" height="3.468" x="9.705" y="9.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24154"/></filter><filter id="iguW2vb" width="3.218" height="3.468" x="19.218" y="8.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24154"/></filter><filter id="i9MChhd" width="3.148" height="3.148" x="19.253" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".25"/></filter><filter id="inVJKwc" width="2.948" height="2.948" x="9.86" y="9.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".2"/></filter><filter id="icsUPqz" width="10.191" height="11.127" x="10.905" y="5.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24154"/></filter><filter id="iQ0Jkyb" width="2.877" height="3.682" x="14.399" y="9.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".25"/></filter><filter id="ita3sod" width="2.377" height="3.182" x="14.811" y="9.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".125"/></filter><filter id="i86HPXM" width="3.001" height="1.286" x="16.942" y="9.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24154"/></filter><filter id="icqd3nb" width="3.001" height="1.286" x="12.057" y="9.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24154"/></filter><filter id="iVb8Znl" width="2.453" height="1.091" x="12.192" y="7.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24154"/></filter><filter id="iPpfcfc" width="2.453" height="1.091" x="17.609" y="7.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24154"/></filter><filter id="iqzZulb" width=".787" height=".696" x="17.448" y="9.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".05"/></filter><filter id="iEZQY1b" width=".891" height=".913" x="18.288" y="9.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".1"/></filter><filter id="izBf7Fc" width=".986" height="1.04" x="13.845" y="9.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".1"/></filter><filter id="iV3MzVd" width=".913" height=".704" x="13.09" y="9.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".05"/></filter><filter id="ixpfBCc" width="2.661" height="1.378" x="17.439" y="7.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".2"/></filter><filter id="iIRfHZb" width="2.661" height="1.378" x="11.988" y="7.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".2"/></filter><filter id="iUoVcgb" width="4.287" height="5.25" x="9.741" y="3.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".25"/></filter><filter id="ijSr5kd" width="8.914" height="5.78" x="12.683" y="2.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".125"/></filter><filter id="i16uEnd" width="1.145" height="2.31" x="12.809" y="3.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24154" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-health-worker-medium-light" /></template>
<style>
.a3iiymleb {
  stop-color: var(--svg-color--8e5b4b, #8E5B4B);
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.aopy3pbzd {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m19.732 8.465l-.138.23za.268.268 0 0 1-.275.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.109a3.3 3.3 0 0 1 .559.238l.009.006z");
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bfpb1bcgi {
  stop-color: var(--svg-color--cf9c8f, #CF9C8F);
}

.bl736eqew {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.19 26.363h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c0x_nlp-j {
  d: path("M16.65 21.76c-.263.516-.263.942-.263 1.306v2.992c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.753-.83a.23.23 0 0 1 .129-.38l.783-.14a.23.23 0 0 0 .188-.25l-.187-2.06a.25.25 0 0 0-.113-.186a10.5 10.5 0 0 0-2.426-1.134a.3.3 0 0 0-.04.08z");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c4269f9-h {
  d: path("M11.106 4.686c.62-.553 1.517-.559 2.02-.47l.402 1.291c-.257-.039-.486.05-.679.235c-.453 1.676-2.162 1.425-2.498 2.682c-.15-1.492-.318-2.783.755-3.738");
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c648-8dat {
  d: path("M18.119 9.814c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.cfg0tb7kn {
  d: path("M15.986 15.48c-2.74 0-5.3 1.06-7.21 2.84v11.75h14.38V18.29a10.54 10.54 0 0 0-7.17-2.81");
}

.cjp7vbcdm {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.149 8.327c-.323-.078-1.125-.039-1.661.345");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.d34q2nbhk {
  d: path("M16.355 15.48c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.d71a5hb6m {
  fill-rule: evenodd;
  d: path("M15.935 15.19a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 1 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.d7t-w3bii {
  d: path("M26.826 28.04c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59v11.78h3.65z");
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.do-bxqb6m {
  d: path("M19.675 26.8a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.dxszyubmb {
  stop-color: var(--svg-color--d3cfda, #D3CFDA);
}

.e---z_byu {
  stop-color: var(--svg-color--ad9ec2, #AD9EC2);
}

.e1blajbcf {
  d: path("M11.314 12.309a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.e6fuuiw3e {
  stop-color: var(--svg-color--261943, #261943);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.fisbdwbzk {
  d: path("M20.827 12.309a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
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

.fv5w29bdg {
  stop-color: var(--svg-color--261943, #261943);
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g-038cbdt {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.602 8.922l-.004.003a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.01-.006a2 2 0 0 1 .148-.076c.098-.047.239-.107.41-.162c.34-.109.815-.2 1.328-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gbq2cubxr {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.858 10.13c-.265-.466-.669-.835-1.537-.835c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.08-.45");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gndpcrt6r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.109 4.158c.023.243.234 1.156.544 1.71");
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gxfu6xbrp {
  d: path("M15.985 18.79a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.gxm-dc6uw {
  stop-color: var(--svg-color--a46e69, #A46E69);
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hiuialb7f {
  d: path("m5.926 22.84l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67V18.32a10.56 10.56 0 0 0-2.85 4.52");
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.hvnxgib9j {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.207 20.224l.732.13a.213.213 0 0 1 .12.352l-.704.77a.216.216 0 0 0 .01.297l4.505 4.598c.112.112.306.037.306-.12v-3.329c0-.037-.009-.065-.018-.102l-2.54-5.887a.15.15 0 0 0-.038-.065a9.7 9.7 0 0 0-2.364 1.122l-.186 2.002a.214.214 0 0 0 .177.232");
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.i62jx7m-s {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.518a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.idrj4ac7u {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.609 9.354c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.ieh-bmbmr {
  d: path("M19.675 26.25a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.iqq-d2brk {
  stop-color: var(--svg-color--574379, #574379);
  stop-opacity: 0;
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.j9x2zdbja {
  d: path("M10.913 9.437h.012l-.01-.265l-.01-.306c.02-.95.574-1.316.81-1.439l.051-.02q.028-.013.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.136 1.332l-.12 3.073c-.123 2.803-2.311 4.685-4.982 4.685s-4.86-1.882-4.984-4.685z");
}

.jbi-edbxv {
  cx: 13.547px;
  cy: 10.007px;
  rx: 0.39px;
  ry: 0.197px;
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.k_rid7bmg {
  d: path("m10.915 9.172l-.01-.306c.02-.95.574-1.316.81-1.439l.051-.02q.028-.013.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.136 1.332l-.12 3.073c-.123 2.803-2.311 4.685-4.982 4.685s-4.86-1.882-4.984-4.685z");
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k34g2lbpi {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.618 10.339l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.k5_wf-bwi {
  stop-color: var(--svg-color--4b2f74, #4B2F74);
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.keav6qbwv {
  fill-rule: evenodd;
  d: path("M12.205 20.93c-.94 0-1.71.762-1.71 1.71v3.3h.67a.49.49 0 0 1 0 .98h-1a.65.65 0 0 1-.65-.65v-3.63a2.69 2.69 0 0 1 5.38 0v3.63c0 .36-.29.65-.65.65h-.93a.49.49 0 1 1 0-.98h.6v-3.3c0-.94-.762-1.71-1.71-1.71");
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
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

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.laxsilb3j {
  stop-color: var(--svg-color--755a97, #755A97);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll7oxmbau {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
  stop-opacity: 0;
}

.lnyefdcqm {
  stop-color: var(--svg-color--c8bfd6, #C8BFD6);
}

.lpc21p-wa {
  stop-color: var(--svg-color--553c83, #553C83);
}

.lvfx8kb6o {
  d: path("M20.827 11.774a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lxiaxgu3j {
  stop-color: var(--svg-color--b58876, #B58876);
}

.m48yk268l {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.608 10.477l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.494-.377-.614 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mu_doqb_t {
  d: path("M15.397 2.91c-1.133-.25-2.347.955-2.464 1.374c1.542 3.62 3.91 3.275 6.537 2.983c1.572-.175 1.743.542 1.877.889c-.436-4.057-3.37-4.677-5.95-5.247");
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.mzjj6abkt {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.94 8.327c.322-.078 1.124-.039 1.66.345");
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.nd_b8e5hf {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.119 9.814c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nrx5bzr9s {
  stop-color: var(--svg-color--756a93, #756A93);
}

.o-3cwm4mc {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.518a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
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

.ov9b4g-co {
  fill-rule: evenodd;
  d: path("M14.896 23.8v2.47c0 .36-.29.65-.651.65h-.58v-.98h.25V23.8z");
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p5_0bzbaz {
  stop-color: var(--svg-color--574379, #574379);
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pew3kybpl {
  cx: 13.547px;
  cy: 10.007px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pjct3_xqc {
  d: path("M11.334 11.774a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.q_nmtdtfz {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.844 27.028a1.1 1.1 0 1 0 0-2.198a1.1 1.1 0 0 0 0 2.198");
}

.q0omcobvq {
  fill: var(--svg-color--564a7b, #564A7B);
  fill-rule: evenodd;
  d: path("M15.935 15.19a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 1 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qkd1vh4ud {
  d: path("M18.979 10.4a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qt7d8ab9i {
  fill-rule: evenodd;
  d: path("M23.185 12.11c.213-.436.324-.922.324-1.428c0-.467-.096-.905-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232A3.3 3.3 0 0 0 16 2.17a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.232q-.043 0-.085.002A3.3 3.3 0 0 0 9.564 7.08v.01a3.24 3.24 0 0 1-.527 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.456m-12.26-2.673h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.955-1.332-1.135-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.195a2.3 2.3 0 0 1-1.241 1.254q-.028.013-.051.02c-.236.123-.79.49-.81 1.44l.01.306z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.s9u9atb0s {
  d: path("m15.618 10.339l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.sgt5sn5oc {
  stop-color: var(--svg-color--bd8381, #BD8381);
  stop-opacity: 0;
}

.shno8vb_u {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.602 13.223a3 3 0 0 0 1.398.338c.518 0 .994-.123 1.398-.338a.205.205 0 0 1 .247.04c.059.063.08.16.022.25m-3.065-.29l3.023.263m-3.023-.264a.204.204 0 0 0-.248.044a.196.196 0 0 0-.02.248m.268-.291l-.227.263m3.292.027l-.042-.027m.042.027l-.042-.027m.042.027a1.982 1.982 0 0 1-3.333 0m3.29-.027a1.932 1.932 0 0 1-3.249 0m-.041.028l.041-.028m-.041.028l.041-.028");
}

.skbyo7b7w {
  d: path("M18.184 9.625a.892.892 0 0 1 .86 1.128H17.32a.896.896 0 0 1 .864-1.128");
}

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.sp4_sibjj {
  stop-color: var(--svg-color--5d4f77, #5D4F77);
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.sruu51y8f {
  stop-color: var(--svg-color--271b48, #271B48);
  stop-opacity: 0;
}

.t5ewf8b-q {
  stop-color: var(--svg-color--ce9591, #CE9591);
  stop-opacity: 0;
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.t8pzkjb2s {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.142 10.13c.266-.466.669-.835 1.538-.835c.38 0 .746.105 1.072.369c.27.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tnslzrbma {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.827 11.774a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.u-u60pbom {
  d: path("M14.631 10.413c0-.288-.234-.48-.298-.538l-.288.278l.177.362z");
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v3kg3vvpv {
  d: path("M16.025 15.48h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.vbqduhb-c {
  d: path("M13.816 9.625a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.vh23662ds {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.334 11.774a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w_gx_6l5c {
  stop-color: var(--svg-color--271b48, #271B48);
}

.w-_6jxb_z {
  stop-color: var(--svg-color--efeafb, #EFEAFB);
}

.w0rhj52ia {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
  stop-opacity: 0;
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wqc_w2bup {
  fill-rule: evenodd;
  d: path("M9.514 26.26v-2.47h.982v2.139h.249v.981h-.58a.65.65 0 0 1-.65-.65");
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
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

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.y_w8ygbcs {
  d: path("m21.893 20.224l-.732.13a.213.213 0 0 0-.12.352l.704.77a.216.216 0 0 1-.01.297L17.23 26.37c-.112.112-.306.037-.306-.12v-3.329c0-.037.009-.065.018-.102l2.54-5.887a.15.15 0 0 1 .038-.065a9.7 9.7 0 0 1 2.364 1.122l.186 2.002a.214.214 0 0 1-.177.232");
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.y623nhl9a {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 9.354c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.ygcxgdb6u {
  d: path("M15.37 21.76c.263.516.263.942.263 1.306v2.992c0 .17-.209.26-.328.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.119-.13.05-.35-.129-.38l-.783-.14a.23.23 0 0 1-.189-.25l.188-2.06a.25.25 0 0 1 .113-.186a10.5 10.5 0 0 1 2.426-1.134a.3.3 0 0 1 .04.08z");
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zm--4cwlh {
  d: path("M16.493 22.584c0-.04-.01-.203 0-.243l2.662-6.292c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.362c.01.03.055.05.055.09l.055 3.598h.01v3.97h.79V26.1l.078-3.415z");
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
