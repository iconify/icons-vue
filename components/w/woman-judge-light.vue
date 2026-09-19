<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGG8N5n)"><path fill="url(#iLooP6c)" clip-rule="evenodd" class="yvj74cbuf"/><path fill="url(#iiXRHrd)" clip-rule="evenodd" class="yvj74cbuf"/><path fill="url(#iVpmawb)" clip-rule="evenodd" class="yvj74cbuf"/><path fill="url(#i5JWDje)" clip-rule="evenodd" class="yvj74cbuf"/><path fill="url(#in1o0Jb)" clip-rule="evenodd" class="yvj74cbuf"/><path fill="url(#im6jc3b)" clip-rule="evenodd" class="yvj74cbuf"/><path fill="url(#i0awMib)" clip-rule="evenodd" class="yvj74cbuf"/><path fill="url(#iNOeteV)" clip-rule="evenodd" class="yvj74cbuf"/><path fill="url(#ixnIv0b)" clip-rule="evenodd" class="yvj74cbuf"/><path fill="url(#iGdgbSC)" clip-rule="evenodd" class="yvj74cbuf"/><path fill="url(#iuOq0me)" clip-rule="evenodd" class="yvj74cbuf"/></g><path fill="url(#izyIeqe)" class="q36oaq7pj"/><path fill="url(#iy4jJXn)" class="q36oaq7pj"/><path fill="url(#iYBKkSf)" class="q36oaq7pj"/><path fill="url(#icj5YGb)" class="q36oaq7pj"/><path fill="url(#iRx474d)" class="oou8kcc6v"/><path fill="url(#iTKDTse)" class="oou8kcc6v"/><path fill="url(#iDZUUxe)" class="oou8kcc6v"/><path fill="url(#i2rcz6d)" class="oou8kcc6v"/><path fill="url(#iNNKL4d)" class="y-4nqebtf"/><path fill="url(#ifFd45d)" class="y-4nqebtf"/><path fill="url(#iXh35tc)" class="m7r00zbzx"/><path fill="url(#iikJnzd)" class="m7r00zbzx"/><path fill="url(#iX7mRmc)" class="m7r00zbzx"/><path fill="url(#iOSfphm)" class="c1vcgu6ea"/><path fill="url(#in0lc3i)" class="c1vcgu6ea"/><path fill="url(#iJCaZGW)" class="y9_bjubda"/><path fill="url(#it4ewhb)" class="y9_bjubda"/><g filter="url(#iRUhOpd)"><path fill="url(#iWhF86d)" class="b1al3kbrr"/><path fill="url(#iFwUuHc)" class="b1al3kbrr"/><path fill="url(#idRHvhb)" class="b1al3kbrr"/><path fill="url(#iTnXCSc)" class="b1al3kbrr"/><path fill="url(#icRQlCN)" class="b1al3kbrr"/></g><rect fill="url(#i4H8EEe)" class="u06lab1np"/><rect fill="url(#iNpq18b)" class="u06lab1np"/><g filter="url(#i11hdkc)"><path fill="url(#ic7O2Xc)" class="jllthzqmq"/></g><g filter="url(#iXMjdYc)"><path fill="url(#ieZMCdb)" class="kap3uid5w"/></g><g filter="url(#ikHxnwb)"><path fill="url(#iF3dOQe)" class="voim6bbmo"/></g><g filter="url(#is26lhe)"><path stroke="url(#ibbYeEc)" class="kgvzf1buy"/></g><g filter="url(#ieGlOvA)"><path stroke="url(#iIppTIb)" class="hweolzbsy"/></g><g filter="url(#iSzid4b)"><path stroke="url(#iS1nrnd)" class="mb3d47v9y"/></g><g filter="url(#irf7fye)"><path fill="url(#iDITqHd)" class="cx6gu0b0b"/><path fill="url(#i54ZnFd)" class="cx6gu0b0b"/></g><path fill="url(#iADfSge)" class="nj8jdqb3l"/><path fill="url(#iJ4HTbb)" class="nj8jdqb3l"/><path fill="url(#iGw3rfd)" class="nj8jdqb3l"/><path fill="url(#iKJrDob)" class="nj8jdqb3l"/><path fill="url(#iPBrhcb)" class="nj8jdqb3l"/><path fill="url(#ikPDHRb)" class="pmh5irotb"/><path fill="url(#ix7VU2c)" class="pmh5irotb"/><path fill="url(#iJUNBce)" class="pmh5irotb"/><path fill="url(#iklGphd)" class="pmh5irotb"/><path fill="url(#ia9KDsc)" class="cuin_5bnf"/><path fill="url(#iKXQm2c)" class="cuin_5bnf"/><path fill="url(#ieBkvIe)" class="cuin_5bnf"/><path fill="url(#iHkt3Rc)" class="dps03v2dp"/><path fill="url(#iLY6Zfd)" class="f4j9_7boa"/><g filter="url(#iRrcY3b)"><path fill="url(#ijyGGfn)" class="zlvy0p07o"/></g><g filter="url(#icdAxgJ)"><path fill="url(#iSkKC5c)" class="xj5cw0b-q"/><path fill="url(#ijXkp0c)" class="xj5cw0b-q"/></g><g filter="url(#ibvgqjj)"><path class="y_hb5vqel"/><path fill="url(#iqou8yd)" class="jmxrwtbma"/></g><g filter="url(#iSbBC4c)"><path class="ld3x0nq5x"/><path fill="url(#ijxxhkd)" class="k8od0nbtm"/></g><g filter="url(#iY7mSpe)"><path fill="url(#isDETmc)" class="x0oa84bwc"/><path fill="url(#i8Q63GQ)" class="x0oa84bwc"/><path fill="url(#i1Gr5Fe)" class="x0oa84bwc"/><path fill="url(#iIly0Vn)" class="x0oa84bwc"/><path fill="url(#i1fKNOI)" class="x0oa84bwc"/><path fill="url(#ieKn6Bb)" class="x0oa84bwc"/><path fill="url(#iH7fwRc)" class="x0oa84bwc"/></g><path fill="url(#iiEB7Dc)" class="x0oa84bwc"/><path fill="url(#ioHgpmd)" class="x0oa84bwc"/><g filter="url(#inIPhZd)"><path class="xjijh-bfb"/></g><g filter="url(#iaedcpB)"><path class="v_90q1b3h"/><path fill="url(#ih2ELge)" class="mbrahpb3f"/><path fill="url(#ivmMvOd)" class="mbrahpb3f"/><path fill="url(#i0h3dNe)" class="mbrahpb3f"/><path fill="url(#imXXC3c)" class="mbrahpb3f"/></g><path fill="url(#iiwtq4c)" class="mbrahpb3f"/><path fill="url(#ioOZ0we)" class="mbrahpb3f"/><path stroke="url(#iyca1Bc)" class="yt9bvobid"/><g filter="url(#iVXRHKb)"><path class="gunq4lh6f"/></g><g filter="url(#ijrl9cd)"><path class="brzf-g-yt"/></g><g filter="url(#iqA99ko)"><path class="hnvubfb-k"/></g><g filter="url(#iva4B8j)"><path clip-rule="evenodd" class="zg3-y9bir"/></g><path class="oed33gbfo"/><path fill="url(#iqiWKbh)" class="iske6vs0z"/><path class="e2rh0db8f"/><g filter="url(#iyCv8Tb)"><path class="gequ-ibtv"/><path fill="url(#iVngGwh)" class="a4qswebkb"/></g><g filter="url(#iluuyid)"><path fill="url(#iNNwZlz)" class="n8sr9y_jh"/></g><path class="e-nguc6-j"/><path fill="url(#iuHY8Xc)" class="tjn5hmuwm"/><path class="pe-p3z7kg"/><g filter="url(#i4IICFe)"><path fill="url(#icppAde)" class="aeibdzvho"/></g><g filter="url(#iKCIjAc)"><ellipse transform="rotate(-27.914 13.732 10.059)" class="ygiqhqbvs"/><ellipse fill="url(#iX7Ovtc)" transform="rotate(-27.914 13.732 10.059)" class="fipnx2mxo"/></g><g filter="url(#ieYLI3c)"><path class="j1ozayf8y"/></g><g filter="url(#im18Ehe)"><path class="dxx7qmbqz"/></g><g filter="url(#iXX2xfb)"><path class="rqtlk4b6p"/><path fill="url(#iCd41ve)" class="z8vggza1f"/></g><g filter="url(#iCfM2Tt)"><path class="awl3q-bgh"/><path fill="url(#iE3lpzd)" class="spouuqjqf"/><path fill="url(#iLkmv9r)" class="spouuqjqf"/></g><g filter="url(#inNJwPK)"><path stroke="url(#irdZ9Sd)" class="pn8qowm1t"/></g><g filter="url(#iNftfPb)"><path class="cw5mw8q8a"/></g><defs><radialGradient id="iiXRHrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 15.883 13.252)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iVpmawb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 13.068 13.52)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i5JWDje" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.96 8.289)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="in1o0Jb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.389 7.78)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="im6jc3b" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 12.665 2.692)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i0awMib" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 10.02 6.946)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iNOeteV" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 23.694 9.9)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="ixnIv0b" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.725 8.08)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iGdgbSC" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.13 -3.749)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iuOq0me" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 10.043 9.864)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="icj5YGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.45313 -5.35592 0 16.17 16.72)" gradientUnits="userSpaceOnUse"><stop class="u4dm99tvf"/><stop offset="1" class="pzxsbj1yt"/></radialGradient><radialGradient id="iRx474d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 5.095 29.996)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iTKDTse" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.943 29.996)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iDZUUxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.943 23.047)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="iNNKL4d" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 25.095 4.501)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="ifFd45d" cx="0" cy="0" r="1" gradientTransform="matrix(.55553 12.0481 -.71816 .03311 23.225 23.15)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iXh35tc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.27137 -3.54923 0 16.94 16.273)" gradientUnits="userSpaceOnUse"><stop class="fqxr12j4i"/><stop offset="1" class="rhyy10bsj"/></radialGradient><radialGradient id="iikJnzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.42297 -2.45165 0 16.17 15.185)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="c1m1iubdt"/><stop offset=".923" class="uupgmqj6k"/></radialGradient><radialGradient id="iX7mRmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42187 -.53125 0 14.86 16.03)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="n50spdbkh"/><stop offset="1" class="a-vopxe4e"/></radialGradient><radialGradient id="iOSfphm" cx="0" cy="0" r="1" gradientTransform="rotate(154.355 11.51 15.16)scale(2.33554 2.29591)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="in0lc3i" cx="0" cy="0" r="1" gradientTransform="rotate(-37.372 48.444 -29.227)scale(.9457 .72531)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="iJCaZGW" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 26.271 24.28)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="iFwUuHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.037 25.3)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="idRHvhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.037 26.595)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iTnXCSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.037 27.845)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="icRQlCN" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.037 29.197)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i4H8EEe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.717 21.457)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="iDITqHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.3125 12.819 0 16.151 23.402)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="rr16fpbgs"/><stop offset="1" class="gvd3e3nnk"/></radialGradient><radialGradient id="i54ZnFd" cx="0" cy="0" r="1" gradientTransform="rotate(-94.385 20.552 4.372)scale(10.6778 18.1021)" gradientUnits="userSpaceOnUse"><stop offset=".721" class="p3kckzh8s"/><stop offset="1" class="nqv_-mmyu"/></radialGradient><radialGradient id="iGw3rfd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.87 17.389)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="iklGphd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.584 17.215)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="ieBkvIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.35 17.465)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="iSkKC5c" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 23.484 -17.32)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="ijXkp0c" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 21.255 9.07)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iqou8yd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.577 10.864)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="ijxxhkd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.584 10.751)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="isDETmc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -4.01413 -8.70492 19.044 10.214)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="i8Q63GQ" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 19.437 11.576)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="i1Gr5Fe" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.805 17.543)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iIly0Vn" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -7.78405 0 16.185 9.997)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="i1fKNOI" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.417 6.847)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="ieKn6Bb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.486 9.795)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iH7fwRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 14.108 9.567)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="iiEB7Dc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.28 11.283)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="ioHgpmd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 14 4.215)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="ih2ELge" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.97 12.01)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="imXXC3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.73 12.221)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="ioOZ0we" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.478 8.382)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="iqiWKbh" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.367 10.154)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVngGwh" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.139 10.238)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuHY8Xc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 14.003 10.154)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iX7Ovtc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.965 -1.565)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iCd41ve" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.521 -4.183)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iE3lpzd" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.16 7.102)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iLkmv9r" cx="0" cy="0" r="1" gradientTransform="matrix(-.21034 1.3672 -2.94144 -.45253 16.395 3.196)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><linearGradient id="iLooP6c" x1="20.878" x2="14.073" y1="3.799" y2="16.403" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="izyIeqe" x1="16.172" x2="16.172" y1="15.537" y2="30.421" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="iy4jJXn" x1="23.599" x2="21.068" y1="26.59" y2="26.621" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="iYBKkSf" x1="8.627" x2="10.843" y1="26.405" y2="26.405" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="i2rcz6d" x1="9.091" x2="8.656" y1="28.062" y2="28.062" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="it4ewhb" x1="25.634" x2="25.662" y1="21.992" y2="22.348" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="iWhF86d" x1="27.628" x2="23.6" y1="28.058" y2="28.058" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="iNpq18b" x1="25.644" x2="25.644" y1="20.808" y2="21.269" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="ic7O2Xc" x1="17.222" x2="17.222" y1="29.599" y2="22.923" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ieZMCdb" x1="13.215" x2="13.215" y1="29.599" y2="22.923" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iF3dOQe" x1="21.209" x2="21.209" y1="29.599" y2="22.923" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ibbYeEc" x1="24.123" x2="25.832" y1="26.066" y2="26.066" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iIppTIb" x1="24.045" x2="25.754" y1="27.371" y2="27.371" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iS1nrnd" x1="24.123" x2="25.832" y1="28.675" y2="28.675" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iADfSge" x1="27.912" x2="24.537" y1="20.715" y2="20.34" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="iJ4HTbb" x1="25.632" x2="25.632" y1="20.98" y2="20.465" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="iKJrDob" x1="25.632" x2="25.632" y1="16.835" y2="17.465" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="iPBrhcb" x1="23.335" x2="24.077" y1="19.182" y2="19.182" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="ikPDHRb" x1="23.506" x2="22.209" y1="18.966" y2="18.966" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="ix7VU2c" x1="23.756" x2="23.365" y1="19.246" y2="19.246" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="iJUNBce" x1="22.96" x2="22.96" y1="21.076" y2="20.414" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="ia9KDsc" x1="29.207" x2="27.587" y1="19.413" y2="19.413" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="iKXQm2c" x1="28.506" x2="28.506" y1="21.051" y2="20.527" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="iHkt3Rc" x1="9" x2="23.376" y1="15.561" y2="15.561" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iLY6Zfd" x1="9" x2="23.376" y1="15.531" y2="15.531" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ijyGGfn" x1="9.89" x2="12.85" y1="10.839" y2="10.839" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="ivmMvOd" x1="15.246" x2="16.185" y1="12.082" y2="12.082" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="i0h3dNe" x1="16.185" x2="16.185" y1="12.882" y2="12.271" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iiwtq4c" x1="16.263" x2="16.263" y1="12.855" y2="12.716" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="iyca1Bc" x1="15.121" x2="15.582" y1="14.291" y2="13.579" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iNNwZlz" x1="19.145" x2="18.831" y1="10.208" y2="10.402" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icppAde" x1="14.747" x2="14.433" y1="10.208" y2="10.402" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irdZ9Sd" x1="13.294" x2="13.838" y1="4.553" y2="5.827" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><filter id="iGG8N5n" width="15.268" height="15.768" x="8.676" y="1.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/></filter><filter id="iRUhOpd" width="4.468" height="5.556" x="23.6" y="24.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/></filter><filter id="i11hdkc" width="1.192" height="6.826" x="15.589" y="23.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".125"/></filter><filter id="iXMjdYc" width="1.192" height="6.826" x="11.583" y="23.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".125"/></filter><filter id="ikHxnwb" width="1.192" height="6.826" x="19.576" y="23.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".125"/></filter><filter id="is26lhe" width="2.097" height=".3" x="23.973" y="25.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".05"/></filter><filter id="ieGlOvA" width="2.097" height=".3" x="23.895" y="27.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".05"/></filter><filter id="iSzid4b" width="2.097" height=".3" x="23.973" y="28.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".05"/></filter><filter id="irf7fye" width="12.911" height="8.522" x="9.695" y="15.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.756863 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/></filter><filter id="iRrcY3b" width="3.368" height="3.218" x="9.89" y="9.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/></filter><filter id="icdAxgJ" width="3.218" height="3.468" x="19.403" y="8.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/></filter><filter id="ibvgqjj" width="3.148" height="3.148" x="19.438" y="9.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".25"/></filter><filter id="iSbBC4c" width="2.948" height="2.948" x="10.045" y="9.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".2"/></filter><filter id="iY7mSpe" width="10.191" height="11.277" x="11.09" y="5.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/></filter><filter id="inIPhZd" width="2.877" height="3.682" x="14.584" y="9.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".25"/></filter><filter id="iaedcpB" width="2.377" height="3.182" x="14.996" y="9.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".125"/></filter><filter id="iVXRHKb" width="3.001" height="1.285" x="17.127" y="9.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/></filter><filter id="ijrl9cd" width="3.001" height="1.285" x="12.242" y="9.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/></filter><filter id="iqA99ko" width="2.453" height="1.091" x="12.377" y="7.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/></filter><filter id="iva4B8j" width="2.453" height="1.091" x="17.794" y="7.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/></filter><filter id="iyCv8Tb" width=".787" height=".696" x="17.633" y="9.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".05"/></filter><filter id="iluuyid" width=".891" height=".913" x="18.473" y="9.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".1"/></filter><filter id="i4IICFe" width=".986" height="1.04" x="14.03" y="9.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".1"/></filter><filter id="iKCIjAc" width=".913" height=".705" x="13.275" y="9.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".05"/></filter><filter id="ieYLI3c" width="2.261" height=".978" x="17.825" y="8.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".1"/></filter><filter id="im18Ehe" width="2.261" height=".978" x="12.373" y="8.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".1"/></filter><filter id="iXX2xfb" width="4.212" height="4.513" x="9.931" y="3.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/><feGaussianBlur result="effect2_foregroundBlur_4002_1741" stdDeviation=".15"/></filter><filter id="iCfM2Tt" width="8.767" height="5.782" x="13.015" y="2.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1741"/><feGaussianBlur result="effect2_foregroundBlur_4002_1741" stdDeviation=".125"/></filter><filter id="inNJwPK" width="1.145" height="2.31" x="12.994" y="3.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".1"/></filter><filter id="iNftfPb" width="6.427" height="3.372" x="15.603" y="4.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1741" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-judge-light" /></template>
<style>
.a-vopxe4e {
  stop-color: var(--svg-color--cf9c8e, #CF9C8E);
  stop-opacity: 0;
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a4qswebkb {
  d: path("M18.304 9.866c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.aeibdzvho {
  d: path("M14.816 10.465c0-.288-.234-.48-.298-.539l-.288.28l.178.36z");
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.awl3q-bgh {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.582 2.96c-1.133-.25-2.15.88-2.267 1.3c1.052 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.b1al3kbrr {
  d: path("M23.6 25.322a.73.73 0 0 1 .726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.brzf-g-yt {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.043 10.182c-.265-.466-.669-.835-1.537-.835c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.08-.45");
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c1m1iubdt {
  stop-color: var(--svg-color--b88168, #B88168);
  stop-opacity: 0;
}

.c1vcgu6ea {
  d: path("M26.959 22.929c.532 0 .959.427.959.959v2.188H26.01v-2.188a.94.94 0 0 1 .948-.959");
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuin_5bnf {
  d: path("M28.704 16.951h-.614a.505.505 0 0 0-.503.504v3.022c0 .272.221.503.503.503h.613a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cw5mw8q8a {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.591 6.57l-1.425.263a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.cx6gu0b0b {
  d: path("M13.237 16.075a.196.196 0 0 0-.221-.176c-1.073.163-1.98.713-2.909 1.244c-.195.111-.357.285-.392.508q-.02.12-.02.247c0 .6.333 1.12.824 1.39c.057.03.076.104.041.158a1.582 1.582 0 0 0 1.419 2.43a.114.114 0 0 1 .119.121l-.004.112a1.582 1.582 0 0 0 2.498 1.29a.114.114 0 0 1 .166.038a1.582 1.582 0 0 0 2.786 0a.114.114 0 0 1 .166-.038a1.582 1.582 0 0 0 2.495-1.402a.114.114 0 0 1 .118-.12l.084.002a1.582 1.582 0 0 0 1.335-2.433a.113.113 0 0 1 .04-.159a1.58 1.58 0 0 0 .805-1.636c-.035-.223-.197-.397-.392-.508c-.928-.53-1.836-1.081-2.909-1.244a.196.196 0 0 0-.221.176c-.19 1.636-1.06 3.258-2.914 3.268c-1.854-.01-2.725-1.632-2.914-3.268");
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dps03v2dp {
  d: path("M16.54 15.532c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.dxx7qmbqz {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.334 8.379c-.323-.079-1.125-.04-1.661.344");
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e-nguc6-j {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.794 9.406c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e2rh0db8f {
  fill: var(--svg-color--000, #000);
  d: path("M17.858 10.57c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f4j9_7boa {
  d: path("M16.21 15.532h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.fipnx2mxo {
  cx: 13.732px;
  cy: 10.059px;
  rx: 0.39px;
  ry: 0.197px;
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.fqxr12j4i {
  stop-color: var(--svg-color--d29b92, #D29B92);
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gequ-ibtv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.304 9.866c.063.085-.07.189-.221.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gunq4lh6f {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.327 10.182c.266-.466.669-.835 1.537-.835c.38 0 .747.105 1.073.369c.27.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.gvd3e3nnk {
  stop-color: var(--svg-color--bdb2af, #BDB2AF);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.hnvubfb-k {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.788 8.974l-.005.002a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.194");
}

.hweolzbsy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.045 27.293h1.797");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.iske6vs0z {
  d: path("M18.37 9.677a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j1ozayf8y {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.125 8.379c.322-.079 1.124-.04 1.66.344");
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.jllthzqmq {
  d: path("M15.839 23.54h.692v6.326h-.692z");
}

.jmxrwtbma {
  d: path("M21.012 11.826a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k8od0nbtm {
  d: path("M11.519 11.826a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kap3uid5w {
  d: path("M11.833 23.54h.692v6.326h-.692z");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kgvzf1buy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.123 25.988h1.797");
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ld3x0nq5x {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.519 11.826a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.m7r00zbzx {
  d: path("M16.17 18.544a2.07 2.07 0 0 1-2.075-2.075v-2.578a2.07 2.07 0 0 1 2.075-2.065c1.149 0 2.075.926 2.075 2.075v2.579a2.083 2.083 0 0 1-2.075 2.064");
}

.mb3d47v9y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.123 28.597h1.797");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbrahpb3f {
  d: path("m15.803 10.39l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n50spdbkh {
  stop-color: var(--svg-color--cf9c8e, #CF9C8E);
}

.n8sr9y_jh {
  d: path("M19.164 10.452a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.nj8jdqb3l {
  d: path("M27.083 16.951h-2.901a.505.505 0 0 0-.504.504v3.022c0 .272.222.503.504.503h2.9a.505.505 0 0 0 .505-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nqv_-mmyu {
  stop-color: var(--svg-color--5f5c5d, #5F5C5D);
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oed33gbfo {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.576 9.406c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.37-1.127");
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.oou8kcc6v {
  d: path("M8.943 29.996v-11.8c-2.356 2.01-3.848 4.986-3.848 8.31v3.49z");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p3kckzh8s {
  stop-color: var(--svg-color--9b999b, #9B999B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pe-p3z7kg {
  fill: var(--svg-color--000, #000);
  d: path("M14.512 10.57a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmh5irotb {
  d: path("M23.178 16.951h-.613a.505.505 0 0 0-.504.504v3.022c0 .272.222.503.504.503h.613a.505.505 0 0 0 .503-.503v-3.022a.51.51 0 0 0-.503-.504");
}

.pn8qowm1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.294 4.21c.023.243.234 1.156.544 1.71");
}

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.pzxsbj1yt {
  stop-color: var(--svg-color--1a121e, #1A121E);
  stop-opacity: 0;
}

.q36oaq7pj {
  d: path("M16.094 15.715c-6.115 0-10.999 4.728-10.999 10.79v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.062-5.037-10.79-11.151-10.79");
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.rhyy10bsj {
  stop-color: var(--svg-color--e4b09e, #E4B09E);
}

.rqtlk4b6p {
  fill: var(--svg-color--232121, #232121);
  d: path("M11.116 4.763c.566-.6 1.636-.6 2.13-.51l.396 1.29c-.252-.04-.478.05-.667.234c-.449 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.rr16fpbgs {
  stop-color: var(--svg-color--ddd3e4, #DDD3E4);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.spouuqjqf {
  d: path("M15.582 2.96c-1.133-.25-2.15.88-2.267 1.3c1.052 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tjn5hmuwm {
  d: path("M14 9.677a.892.892 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u06lab1np {
  width: 2.773px;
  height: 1.082px;
  x: 24.257px;
  y: 20.98px;
  rx: 0.541px;
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u4dm99tvf {
  stop-color: var(--svg-color--1a121e, #1A121E);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.uupgmqj6k {
  stop-color: var(--svg-color--b88168, #B88168);
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v_90q1b3h {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.803 10.39l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.765 0");
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.voim6bbmo {
  d: path("M19.826 23.54h.692v6.326h-.692z");
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.x0oa84bwc {
  d: path("M11.098 9.489h.012l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.438l.051-.02q.028-.013.051-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xj5cw0b-q {
  d: path("M21.012 12.36a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.219");
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xjijh-bfb {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.793 10.529l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.494-.377-.613 0");
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y_hb5vqel {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M21.012 11.826a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.y-4nqebtf {
  d: path("M23.398 29.996v-11.8c2.355 2.01 3.848 4.986 3.848 8.31v2.49a1 1 0 0 1-1 1z");
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.y9_bjubda {
  d: path("M24.879 21.067v6.427h1.51v-6.427z");
}

.ygiqhqbvs {
  cx: 13.732px;
  cy: 10.059px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.yt9bvobid {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.787 13.274a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.021-.25a.205.205 0 0 0-.247-.041a2.96 2.96 0 0 1-1.399.339c-.513 0-.994-.124-1.398-.339Z");
}

.yvj74cbuf {
  fill-rule: evenodd;
  d: path("M23.37 12.161c.213-.435.324-.92.324-1.427a3.3 3.3 0 0 0-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.004a3.24 3.24 0 0 1-.527-1.77v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376A3.3 3.3 0 0 0 13.503 3.6a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004A3.3 3.3 0 0 0 9 12.161a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.455M11.11 9.489h-.012l1.198 2.355c.124 2.803 1.218 0 3.889 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.24 1.255q-.029.013-.052.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z8vggza1f {
  d: path("M11.116 4.763c.566-.6 1.636-.6 2.13-.51l.396 1.29c-.252-.04-.478.05-.667.234c-.449 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.zg3-y9bir {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.917 8.516l-.138.23za.268.268 0 0 1-.276.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .559.238l.009.005l.003.002z");
}

.zlvy0p07o {
  d: path("M11.5 12.36a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.219");
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
