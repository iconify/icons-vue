<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="vmv1chbop"/><path fill="url(#i4CFxsd)" class="v6p9ujc-q"/><path fill="url(#ifobTOc)" class="v6p9ujc-q"/><path fill="url(#iW6gAfr)" class="v6p9ujc-q"/><g filter="url(#ivqY3wE)"><path fill="url(#ipANC1c)" class="nn824ubqo"/></g><g filter="url(#inre5nc)"><path class="gpp7wycfi"/></g><g filter="url(#i7WPKTd)" class="n52mgrb1s"><path class="iyf0cna1x"/></g><path fill="url(#iWfGOLe)" class="bcftfdc4m"/><path fill="url(#ievD9re)" class="bcftfdc4m"/><path fill="url(#imuq4yb)" class="ak3vx915p"/><path fill="url(#iVOG9Kc)" class="ak3vx915p"/><path fill="url(#iojcAKd)" class="ak3vx915p"/><path class="d77th9r6k"/><path fill="url(#iT9eChe)" class="bjetkpbds"/><path fill="url(#iSpf8Ke)" class="bjetkpbds"/><path fill="url(#iPHQm6c)" class="bjetkpbds"/><path fill="url(#i3DcsBc)" class="bjetkpbds"/><path fill="url(#i0nw1we)" class="bjetkpbds"/><path class="vnl9t5uuk"/><path fill="url(#igwft8c)" class="iqc8glb_j"/><path fill="url(#iXjPKdd)" class="iqc8glb_j"/><path fill="url(#iRZGhxe)" class="iqc8glb_j"/><path fill="url(#iDF9RVb)" class="iqc8glb_j"/><path fill="url(#ip5v39c)" class="iqc8glb_j"/><path fill="url(#iOrAB4d)" class="iqc8glb_j"/><path fill="url(#iMh3uXc)" class="iqc8glb_j"/><rect fill="url(#iGZ25fb)" transform="rotate(25.409 21.294 13.466)" class="slgrfcb7b"/><rect fill="url(#iGfq3zd)" transform="rotate(25.409 21.294 13.466)" class="slgrfcb7b"/><rect fill="url(#izKa7jk)" transform="rotate(25.409 21.294 13.466)" class="slgrfcb7b"/><path fill="url(#ifBZ3cd)" class="f2ov9vbbz"/><path fill="url(#i00m6RS)" class="f2ov9vbbz"/><path fill="url(#iRza09n)" class="f2ov9vbbz"/><path fill="url(#iS6OkFI)" class="f2ov9vbbz"/><path fill="url(#i4OeJod)" class="i3dohyb-r"/><path fill="url(#iF0JfEc)" class="i3dohyb-r"/><path fill="url(#it1JxAo)" class="i3dohyb-r"/><path fill="url(#i3d39db)" class="i3dohyb-r"/><path fill="url(#iZaxJub)" class="smf4pibyk"/><path fill="url(#iNHe3sw)" class="smf4pibyk"/><g filter="url(#iOvCToc)"><path fill="url(#isbnBod)" class="kpv06y8mc"/></g><path fill="url(#iHPSyLd)" class="e_ejqyicu"/><path fill="url(#iUuOUsX)" class="e_ejqyicu"/><path fill="url(#iJ2ToNK)" class="e_ejqyicu"/><g filter="url(#iObhD7d)"><path stroke="url(#ir36EUb)" class="g5lypfj3v"/></g><path fill="url(#iUKo63b)" class="dg-gbvf6h"/><g filter="url(#ieKWCcb)"><path clip-rule="evenodd" class="xa036tbdv"/></g><path fill="url(#iL9uuCb)" class="l3qsb7b0m"/><path fill="url(#ihr1vHe)" class="l3qsb7b0m"/><path fill="url(#iYdqisc)" class="l3qsb7b0m"/><path fill="url(#iGk8pGe)" class="l3qsb7b0m"/><path fill="url(#iQ2tFtb)" class="l3qsb7b0m"/><path fill="url(#iPt8qte)" class="l3qsb7b0m"/><path fill="url(#i1cNfEd)" class="knlj00b7g"/><path fill="url(#i8L4tje)" class="knlj00b7g"/><path fill="url(#ilbPIMk)" class="knlj00b7g"/><path fill="url(#i40uNbb)" class="knlj00b7g"/><path fill="url(#iGAbIjb)" class="knlj00b7g"/><g filter="url(#i8bagRb)"><path fill="url(#i6dCrXd)" clip-rule="evenodd" class="mpg30ebba"/></g><g filter="url(#iikPqDT)"><path fill="url(#inVBHsd)" clip-rule="evenodd" class="gii-bpboa"/></g><g filter="url(#iWTPJ3b)"><path class="b3r3yjndl"/></g><g filter="url(#iRvA6fb)"><path class="uprsnpi8o"/></g><path fill="url(#i12riKc)" class="a83xiubrf"/><path class="f9g100bvq"/><path fill="url(#i6kXLsc)" class="yc0ivbchf"/><path class="p_ppzwbju"/><g filter="url(#ih97Ree)"><path fill="url(#iDSCmFd)" class="m2qwe2bau"/></g><g filter="url(#ir344Pb)"><path fill="url(#iH0lRcY)" class="r0ayoebke"/><path fill="url(#i8beXzc)" class="aa1tpqbtw"/></g><g filter="url(#iazp1Ec)"><path stroke="url(#idXXf5r)" class="elsvyab_o"/></g><g filter="url(#iJqgInP)"><path stroke="url(#inBl9kc)" class="ly5mjubfm"/></g><defs><radialGradient id="i4CFxsd" cx="0" cy="0" r="1" gradientTransform="rotate(138.425 10.828 11.945)scale(10.949 12.1957)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="alo19b2xr"/><stop offset="1" class="pwogqrrxj"/></radialGradient><radialGradient id="ifobTOc" cx="0" cy="0" r="1" gradientTransform="rotate(97.998 9.393 11.5)scale(3.12067 2.7251)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="q1ytiebzb"/><stop offset="1" class="qavb5353a"/></radialGradient><radialGradient id="iW6gAfr" cx="0" cy="0" r="1" gradientTransform="matrix(2.23268 1.01324 -4.44268 9.78947 18.297 2)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="mwyzrubgp"/><stop offset="1" class="v0tqkfbzj"/></radialGradient><radialGradient id="ipANC1c" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 3.40625 -3.96363 3.78181 19.602 7.028)" gradientUnits="userSpaceOnUse"><stop class="jwb4ndb5j"/><stop offset=".581" class="b004cib5y"/><stop offset="1" class="vwnsgewhv"/></radialGradient><radialGradient id="iWfGOLe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.25 6.43749 -5.94882 -7.62374 28.634 21.653)" gradientUnits="userSpaceOnUse"><stop class="mkru76bzi"/><stop offset=".745" class="c8iwi0b5h"/></radialGradient><radialGradient id="ievD9re" cx="0" cy="0" r="1" gradientTransform="matrix(-8.55223 2.82027 -1.53546 -4.65615 27.606 17.195)" gradientUnits="userSpaceOnUse"><stop class="i9qb8ebzy"/><stop offset="1" class="naydt1bhx"/></radialGradient><radialGradient id="imuq4yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.54714 -1.6777 0 28.207 17.573)" gradientUnits="userSpaceOnUse"><stop class="zpdkuubmz"/><stop offset="1" class="goykwzbxl"/></radialGradient><radialGradient id="iVOG9Kc" cx="0" cy="0" r="1" gradientTransform="rotate(164.116 13.097 10.994)scale(1.99817 1.27558)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="ivsikybxz"/><stop offset="1" class="u_g01gbit"/></radialGradient><radialGradient id="iojcAKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.80525 -.67168 0 27.54 17.977)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="oh8xzh-ai"/><stop offset="1" class="jy2hb2y-z"/></radialGradient><radialGradient id="iT9eChe" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.5961 -17.2713 0 29.14 3.27)" gradientUnits="userSpaceOnUse"><stop offset=".634" class="pqo3njvzl"/><stop offset="1" class="y6hhg3cco"/></radialGradient><radialGradient id="iPHQm6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.91099 3.08149 0 25.96 5.965)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="u2kebkbsf"/><stop offset="1" class="rw0bm_m_p"/></radialGradient><radialGradient id="i3DcsBc" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 2.3125 -6.50814 6.50814 21.875 2.42)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="k3zuzsc2p"/><stop offset="1" class="ax6-s09hg"/></radialGradient><radialGradient id="i0nw1we" cx="0" cy="0" r="1" gradientTransform="matrix(2.9354 -2.41324 .52813 .6424 20.48 3.34)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="kyixh_zyc"/><stop offset="1" class="nmsds2uhw"/></radialGradient><radialGradient id="igwft8c" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 3.1875 -3.36293 -.49455 18.266 21.664)" gradientUnits="userSpaceOnUse"><stop offset=".44" class="r_zcvubtv"/><stop offset="1" class="mk1v4mb7i"/></radialGradient><radialGradient id="iXjPKdd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.28364 1.52242 -.4085 -.61276 23.784 20.193)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="sa79bdt-x"/><stop offset="1" class="njx-vzunm"/></radialGradient><radialGradient id="iRZGhxe" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 .71875 -1.5551 5.34144 13.514 22.26)" gradientUnits="userSpaceOnUse"><stop class="wf6f59y-w"/><stop offset="1" class="fdf1i_bno"/></radialGradient><radialGradient id="iDF9RVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10937 2.25782 -1.76414 -.8668 16.516 20.898)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="r96zhabkz"/><stop offset="1" class="ua0gepbrj"/></radialGradient><radialGradient id="ip5v39c" cx="0" cy="0" r="1" gradientTransform="matrix(-.56251 2.03125 -1.89905 -.5259 17.97 21.633)" gradientUnits="userSpaceOnUse"><stop offset=".505" class="tepwdy0ri"/><stop offset="1" class="riwrb4b-h"/></radialGradient><radialGradient id="iOrAB4d" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 1.0625 -1.39266 2.4986 21.108 19.823)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="b87ho2b4u"/><stop offset="1" class="y2cwqjbez"/></radialGradient><radialGradient id="iMh3uXc" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -3.09375 1.20203 .78315 20.764 25.791)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="eaxy67k9q"/><stop offset="1" class="ceyou8buv"/></radialGradient><radialGradient id="iGZ25fb" cx="0" cy="0" r="1" gradientTransform="matrix(2.29841 -.29606 .55646 4.31989 21.695 17.768)" gradientUnits="userSpaceOnUse"><stop class="jiq1slpux"/><stop offset="1" class="mgsdx-idi"/></radialGradient><radialGradient id="iGfq3zd" cx="0" cy="0" r="1" gradientTransform="matrix(1.33724 -1.8461 .63208 .45786 23.758 13.26)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="mtz5hyb1s"/><stop offset="1" class="dl1j4hbnd"/></radialGradient><radialGradient id="izKa7jk" cx="0" cy="0" r="1" gradientTransform="rotate(91.156 2.55 19.101)scale(3.52879 .49425)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="ajgvwdsbt"/><stop offset="1" class="rw3jljcef"/></radialGradient><radialGradient id="ifBZ3cd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0625 .25 -.1857 -1.53207 22.014 19.369)" gradientUnits="userSpaceOnUse"><stop offset=".262" class="gbcu-tdfu"/><stop offset="1" class="crid4qi3x"/></radialGradient><radialGradient id="i00m6RS" cx="0" cy="0" r="1" gradientTransform="matrix(1.23147 -.56064 .71722 1.5754 20.096 22.758)" gradientUnits="userSpaceOnUse"><stop class="f19rwmykg"/><stop offset="1" class="u6r-6abtn"/></radialGradient><radialGradient id="iRza09n" cx="0" cy="0" r="1" gradientTransform="matrix(1.0098 4.1052 -2.79361 .68718 19.567 18.929)" gradientUnits="userSpaceOnUse"><stop offset=".874" class="v_4ryrg3h"/><stop offset=".928" class="o6p46_fol"/></radialGradient><radialGradient id="iS6OkFI" cx="0" cy="0" r="1" gradientTransform="rotate(-31.891 43.566 -22.301)scale(2.48437 2.73467)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="k2ulk4b5g"/><stop offset="1" class="nm7y5sbkv"/></radialGradient><radialGradient id="i4OeJod" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14016 .2657 -.20201 -1.62719 20.71 19.439)" gradientUnits="userSpaceOnUse"><stop offset=".262" class="f1k9povrc"/><stop offset="1" class="ejmj7zanp"/></radialGradient><radialGradient id="iF0JfEc" cx="0" cy="0" r="1" gradientTransform="matrix(2.6266 -1.36133 3.15353 6.08455 17.729 22.9)" gradientUnits="userSpaceOnUse"><stop offset=".048" class="i4wy8-jkq"/><stop offset="1" class="w24p3s3hz"/></radialGradient><radialGradient id="it1JxAo" cx="0" cy="0" r="1" gradientTransform="matrix(1.04783 4.36318 -2.90657 .69802 18.17 18.971)" gradientUnits="userSpaceOnUse"><stop offset=".874" class="endxy3vbu"/><stop offset=".928" class="awr5iolwn"/></radialGradient><radialGradient id="i3d39db" cx="0" cy="0" r="1" gradientTransform="matrix(1.9801 -1.4232 1.5372 2.13871 16.512 19.745)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="x6ndepp5s"/><stop offset="1" class="w3m8-rhdb"/></radialGradient><radialGradient id="iZaxJub" cx="0" cy="0" r="1" gradientTransform="rotate(147.824 6.288 12.242)scale(2.9396 1.7606)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="gbcu-tdfu"/><stop offset="1" class="qpu8u57mt"/></radialGradient><radialGradient id="iNHe3sw" cx="0" cy="0" r="1" gradientTransform="rotate(-86.517 20.258 2.735)scale(1.8002 3.61142)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="s4aq1wf1v"/><stop offset="1" class="dmgc9v8bs"/></radialGradient><radialGradient id="iJ2ToNK" cx="0" cy="0" r="1" gradientTransform="matrix(.80876 -2.23473 .60375 .2185 28.633 10.005)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="rmch-r34p"/><stop offset="1" class="s30kpos8d"/></radialGradient><radialGradient id="ir36EUb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 -1.07812 1.80317 1.77704 27.793 14.57)" gradientUnits="userSpaceOnUse"><stop class="dgh7673wc"/><stop offset="1" class="fykpu5bfp"/></radialGradient><radialGradient id="iUKo63b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.63281 0 0 -2.46875 30.063 14.508)" gradientUnits="userSpaceOnUse"><stop class="bw8jp48xz"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iYdqisc" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -1.84375 1.43559 .65696 16.106 27.382)" gradientUnits="userSpaceOnUse"><stop class="edjpuxxda"/><stop offset="1" class="hsa4-s18z"/></radialGradient><radialGradient id="iQ2tFtb" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 -.85937 11.7734 5.35156 16.23 27.195)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="r4zlxac_f"/><stop offset=".314" class="zas4czo7h"/></radialGradient><radialGradient id="iPt8qte" cx="0" cy="0" r="1" gradientTransform="matrix(-.54023 1.26161 -13.46265 -5.76482 17.512 25.758)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="jd57f4p5r"/><stop offset=".417" class="lzqapmb5m"/></radialGradient><radialGradient id="ilbPIMk" cx="0" cy="0" r="1" gradientTransform="rotate(110.556 -.98 19.449)scale(1.335 7.37895)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="g3swuuble"/><stop offset="1" class="dowa19b8a"/></radialGradient><radialGradient id="i40uNbb" cx="0" cy="0" r="1" gradientTransform="matrix(2.28122 -5.49216 3.07789 1.27843 8.637 30)" gradientUnits="userSpaceOnUse"><stop class="wvoeu8l0f"/><stop offset="1" class="ehahb-bmg"/></radialGradient><radialGradient id="iGAbIjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.9375 3.65625 0 15.793 31.008)" gradientUnits="userSpaceOnUse"><stop class="ejezp6b9d"/><stop offset="1" class="mqfkvh4ai"/></radialGradient><radialGradient id="i6dCrXd" cx="0" cy="0" r="1" gradientTransform="rotate(151.783 6.785 7.712)scale(2.18107 6.10648)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jby0r9b2o"/><stop offset="1" class="vixtmqora"/></radialGradient><radialGradient id="inVBHsd" cx="0" cy="0" r="1" gradientTransform="rotate(150.678 5.395 8.048)scale(2.66165 7.63701)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jby0r9b2o"/><stop offset="1" class="vixtmqora"/></radialGradient><radialGradient id="i12riKc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86229 -.38309 .38425 -1.86796 24.962 7.09)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="l6be9nb1o"/><stop offset="1" class="bk8a8mbio"/></radialGradient><radialGradient id="i6kXLsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.44457 -2.29775 0 26.21 7.017)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iH0lRcY" cx="0" cy="0" r="1" gradientTransform="rotate(-121.329 15.022 -3.651)scale(.66917 1.21906)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="ezbem3b1x"/><stop offset=".79" class="kumz7j9en"/></radialGradient><radialGradient id="i8beXzc" cx="0" cy="0" r="1" gradientTransform="rotate(-118.61 15.239 -3.984)scale(.99834 .93105)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ivqY3wE" width="5.5" height="5.75" x="19.009" y="5.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.235294 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2520_10047"/></filter><filter id="inre5nc" width="1.521" height="2.488" x="19.047" y="6.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2520_10047" stdDeviation=".15"/></filter><filter id="i7WPKTd" width="4.075" height="4.075" x="19.721" y="6.213" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2520_10047" stdDeviation=".15"/></filter><filter id="iOvCToc" width="2.665" height="5.492" x="27.594" y="6.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2520_10047" stdDeviation=".25"/></filter><filter id="iObhD7d" width="3.4" height="2.4" x="26.809" y="12.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2520_10047" stdDeviation=".05"/></filter><filter id="ieKWCcb" width="4.05" height="1.761" x="23.259" y="2.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0313726 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2520_10047"/></filter><filter id="i8bagRb" width="3.711" height="5.581" x="13.772" y="8.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.380392 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2520_10047"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.678431 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2520_10047" result="effect2_innerShadow_2520_10047"/></filter><filter id="iikPqDT" width="4.419" height="7.014" x="10.877" y="9.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.380392 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2520_10047"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.678431 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2520_10047" result="effect2_innerShadow_2520_10047"/></filter><filter id="iWTPJ3b" width="3.936" height="6.647" x="11.347" y="9.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2520_10047" stdDeviation=".25"/></filter><filter id="iRvA6fb" width="3.133" height="5.109" x="14.214" y="8.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2520_10047" stdDeviation=".25"/></filter><filter id="ih97Ree" width="1.444" height="1.54" x="26.414" y="6.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2520_10047" stdDeviation=".1"/></filter><filter id="ir344Pb" width="1.35" height="1.095" x="25.086" y="6.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2520_10047" stdDeviation=".05"/></filter><filter id="iazp1Ec" width="3.734" height="1.3" x="23.371" y="3.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2520_10047" stdDeviation=".125"/></filter><filter id="iJqgInP" width="4.123" height="5.795" x="12.472" y="18.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2520_10047" stdDeviation=".25"/></filter><linearGradient id="iSpf8Ke" x1="21.009" x2="23.648" y1="9.384" y2="9.224" gradientUnits="userSpaceOnUse"><stop offset=".278" class="dq03-owgf"/><stop offset="1" class="s16-0b09b"/></linearGradient><linearGradient id="isbnBod" x1="28.482" x2="29.154" y1="11.646" y2="8.931" gradientUnits="userSpaceOnUse"><stop class="zjbt99bun"/><stop offset="1" class="br_70mbyr"/></linearGradient><linearGradient id="iHPSyLd" x1="29.762" x2="29.762" y1="11.805" y2="7.133" gradientUnits="userSpaceOnUse"><stop offset=".528" class="ccao7bc6g"/><stop offset="1" class="vzfqaisso"/></linearGradient><linearGradient id="iUuOUsX" x1="29.798" x2="29.798" y1="11.805" y2="9.96" gradientUnits="userSpaceOnUse"><stop class="t4mvb7bzl"/><stop offset=".721" class="c92nzrvvn"/></linearGradient><linearGradient id="iL9uuCb" x1="12.075" x2="16.28" y1="24.539" y2="29.824" gradientUnits="userSpaceOnUse"><stop class="yf5xvlbkn"/><stop offset="1" class="x9qs5h_6z"/></linearGradient><linearGradient id="ihr1vHe" x1="11.543" x2="14.668" y1="24.414" y2="25.82" gradientUnits="userSpaceOnUse"><stop class="ra9ofbb3d"/><stop offset="1" class="m39r3gb6m"/></linearGradient><linearGradient id="iGk8pGe" x1="15.686" x2="14.663" y1="25.022" y2="27.325" gradientUnits="userSpaceOnUse"><stop class="s38f0kzba"/><stop offset=".16" class="uom2sabkf"/></linearGradient><linearGradient id="i1cNfEd" x1="9.321" x2="17.509" y1="28.059" y2="31.153" gradientUnits="userSpaceOnUse"><stop class="e9tp66euw"/><stop offset="1" class="xg5e2ibba"/></linearGradient><linearGradient id="i8L4tje" x1="15.043" x2="14.446" y1="26.414" y2="27.903" gradientUnits="userSpaceOnUse"><stop class="h5d797b1d"/><stop offset="1" class="pqpr8gbnv"/></linearGradient><linearGradient id="iDSCmFd" x1="27.535" x2="26.976" y1="7.113" y2="7.457" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idXXf5r" x1="26.496" x2="23.559" y1="3.555" y2="4.195" gradientUnits="userSpaceOnUse"><stop class="car3btb1d"/><stop offset="1" class="jsyw4i05b"/></linearGradient><linearGradient id="inBl9kc" x1="14.49" x2="14.49" y1="18.568" y2="23.169" gradientUnits="userSpaceOnUse"><stop class="wj-6zublk"/><stop offset="1" class="aysnvpyem"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-deaf-medium-dark" /></template>
<style>
.a83xiubrf {
  d: path("M23.172 6.805c.006.344.315.508.469.547h1.992l2.164-.711C26.49 5.116 24.643 5.578 23.883 6c-.24.124-.717.46-.711.804");
}

.aa1tpqbtw {
  d: path("M26.297 6.627c.09.171.045.38-.35.413a.36.36 0 0 0-.26.161c-.165.243-.382.163-.47-.002c-.103-.195.055-.48.353-.638s.624-.128.727.066");
}

.ajgvwdsbt {
  stop-color: var(--svg-color--926b58, #926B58);
}

.ak3vx915p {
  d: path("M30.009 12c-1.657 0-3 1.38-3 3.081v3.838c0 1.701 1.343 3.081 3 3.081z");
}

.alo19b2xr {
  stop-color: var(--svg-color--210d2a, #210D2A);
}

.awr5iolwn {
  stop-color: var(--svg-color--895070, #895070);
}

.ax6-s09hg {
  stop-color: var(--svg-color--8a6154, #8A6154);
  stop-opacity: 0;
}

.aysnvpyem {
  stop-color: var(--svg-color--9c7563, #9C7563);
  stop-opacity: 0;
}

.b004cib5y {
  stop-color: var(--svg-color--704339, #704339);
}

.b3r3yjndl {
  stroke: var(--svg-color--d4d2dd, #D4D2DD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.097 10.032c.12 1.041.848 3.49 2.436 5.146");
}

.b87ho2b4u {
  stop-color: var(--svg-color--7c5344, #7C5344);
}

.bcftfdc4m {
  d: path("M30.009 16.84V30H12.626a18.07 18.07 0 0 1 17.383-13.16");
}

.bjetkpbds {
  d: path("M22.268 2c-.377.19-.696.488-.919.86c-.222.372-.34.802-.34 1.241v.141l.227 5.882a8.9 8.9 0 0 0 .687 3.27a8.6 8.6 0 0 0 1.833 2.742a8.1 8.1 0 0 0 2.695 1.793a7.8 7.8 0 0 0 3.145.568h.413V2z");
}

.bk8a8mbio {
  stop-color: var(--svg-color--201724, #201724);
}

.br_70mbyr {
  stop-color: var(--svg-color--734147, #734147);
  stop-opacity: 0;
}

.bw8jp48xz {
  stop-color: var(--svg-color--910555, #910555);
}

.c8iwi0b5h {
  stop-color: var(--svg-color--765dad, #765DAD);
}

.c92nzrvvn {
  stop-color: var(--svg-color--743e56, #743E56);
  stop-opacity: 0;
}

.car3btb1d {
  stop-color: var(--svg-color--323232, #323232);
}

.ccao7bc6g {
  stop-color: var(--svg-color--845b51, #845B51);
}

.ceyou8buv {
  stop-color: var(--svg-color--915471, #915471);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crid4qi3x {
  stop-color: var(--svg-color--8b6351, #8B6351);
}

.d77th9r6k {
  fill: var(--svg-color--835754, #835754);
  d: path("M22.268 2c-.377.19-.696.488-.919.86c-.222.372-.34.802-.34 1.241v.141l.227 5.882a8.9 8.9 0 0 0 .687 3.27a8.6 8.6 0 0 0 1.833 2.742a8.1 8.1 0 0 0 2.695 1.793a7.8 7.8 0 0 0 3.145.568h.413V2z");
}

.dg-gbvf6h {
  d: path("M30.009 13.627a5 5 0 0 1-.25.005a4.84 4.84 0 0 1-2.372-.604a.25.25 0 0 0-.164-.023a.26.26 0 0 0-.145.086a.3.3 0 0 0-.033.333c.293.483.695.881 1.169 1.156a3.07 3.07 0 0 0 1.795.41z");
}

.dgh7673wc {
  stop-color: var(--svg-color--834f5b, #834F5B);
}

.dl1j4hbnd {
  stop-color: var(--svg-color--9f7c71, #9F7C71);
  stop-opacity: 0;
}

.dmgc9v8bs {
  stop-color: var(--svg-color--874a5f, #874A5F);
  stop-opacity: 0;
}

.dowa19b8a {
  stop-color: var(--svg-color--a28be1, #A28BE1);
  stop-opacity: 0;
}

.dq03-owgf {
  stop-color: var(--svg-color--8a5c4d, #8A5C4D);
}

.e_ejqyicu {
  d: path("M30.009 7.313a.72.72 0 0 0-.624.484l-.997 2.878a.74.74 0 0 0-.029.403a.8.8 0 0 0 .19.372a1 1 0 0 0 .368.26c.145.062.306.094.468.095h.624z");
}

.e9tp66euw {
  stop-color: var(--svg-color--7d5dbb, #7D5DBB);
}

.eaxy67k9q {
  stop-color: var(--svg-color--915471, #915471);
}

.edjpuxxda {
  stop-color: var(--svg-color--946fde, #946FDE);
}

.ehahb-bmg {
  stop-color: var(--svg-color--957db3, #957DB3);
  stop-opacity: 0;
}

.ejezp6b9d {
  stop-color: var(--svg-color--946fe2, #946FE2);
}

.ejmj7zanp {
  stop-color: var(--svg-color--8c6353, #8C6353);
}

.elsvyab_o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.746 4a4.95 4.95 0 0 1 2.985-.5");
}

.endxy3vbu {
  stop-color: var(--svg-color--895070, #895070);
  stop-opacity: 0;
}

.ezbem3b1x {
  stop-color: var(--svg-color--c7a7a3, #C7A7A3);
  stop-opacity: 0.25;
}

.f19rwmykg {
  stop-color: var(--svg-color--7b3d61, #7B3D61);
}

.f1k9povrc {
  stop-color: var(--svg-color--a48074, #A48074);
}

.f2ov9vbbz {
  d: path("M19.523 17.464a2.43 2.43 0 0 0-2.296.874l1.227 2.022c-.057.732.094 2.24 1.22 2.381c1.408.177 1.935-1.088 1.995-2.381c.06-1.285-.723-2.664-2.146-2.896");
}

.f9g100bvq {
  fill: var(--svg-color--fff, #fff);
  d: path("M25.839 5.684a2.49 2.49 0 0 0-2.413 1.885c-.08.31.159.607.477.607h3.972a.41.41 0 0 0 .405-.484a2.495 2.495 0 0 0-2.442-2.008");
}

.fdf1i_bno {
  stop-color: var(--svg-color--794455, #794455);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fykpu5bfp {
  stop-color: var(--svg-color--834f5b, #834F5B);
  stop-opacity: 0;
}

.g3swuuble {
  stop-color: var(--svg-color--a28be1, #A28BE1);
}

.g5lypfj3v {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M30.009 13.627a5 5 0 0 1-.25.005a4.84 4.84 0 0 1-2.372-.604a.25.25 0 0 0-.164-.023a.26.26 0 0 0-.145.086a.3.3 0 0 0-.033.333c.293.483.695.881 1.169 1.156a3.07 3.07 0 0 0 1.795.41z");
}

.gbcu-tdfu {
  stop-color: var(--svg-color--a48075, #A48075);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gii-bpboa {
  fill-rule: evenodd;
  d: path("M11.729 9.346a.85.85 0 0 1 .942.747c.207 1.788 1.008 3.299 2.22 4.708a.85.85 0 0 1-1.29 1.108c-1.367-1.59-2.363-3.408-2.619-5.62a.85.85 0 0 1 .747-.943");
}

.goykwzbxl {
  stop-color: var(--svg-color--835056, #835056);
}

.gpp7wycfi {
  stroke: var(--svg-color--8e6a59, #8E6A59);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.422 8.181c0-.689.298-1.308.772-1.737");
}

.h5d797b1d {
  stop-color: var(--svg-color--7d699c, #7D699C);
}

.hsa4-s18z {
  stop-color: var(--svg-color--946fde, #946FDE);
  stop-opacity: 0;
}

.i3dohyb-r {
  d: path("M18.126 17.414c-1.232-.206-2.086.524-2.383.93l1.273 2.148c-.06.779.097 2.381 1.266 2.531c1.46.188 2.008-1.156 2.07-2.53c.062-1.366-.75-2.832-2.227-3.079");
}

.i4wy8-jkq {
  stop-color: var(--svg-color--6d3040, #6D3040);
}

.i9qb8ebzy {
  stop-color: var(--svg-color--50366c, #50366C);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.iqc8glb_j {
  d: path("m19.282 25.914l-.485.922l-6.656-2.5c.052-.255.222-.994.485-1.906c.262-.913.843-2.328 1.14-2.953l6.64 2.187l.737-1.37a1.498 1.498 0 0 1 2.22-.487c.66.495.794 1.43.289 2.083c-.361.466-.76.97-1.105 1.383c-.87 1.045-1.64 1.454-2.297 1.75a2.23 2.23 0 0 0-.968.891");
}

.ivsikybxz {
  stop-color: var(--svg-color--743c52, #743C52);
}

.iyf0cna1x {
  fill: var(--svg-color--633839, #633839);
  d: path("M21.758 9.987a1.737 1.737 0 1 0 0-3.474a1.737 1.737 0 0 0 0 3.474");
}

.jby0r9b2o {
  stop-color: var(--svg-color--cfcbd9, #CFCBD9);
}

.jd57f4p5r {
  stop-color: var(--svg-color--ac8ce9, #AC8CE9);
}

.jiq1slpux {
  stop-color: var(--svg-color--774d3d, #774D3D);
}

.jsyw4i05b {
  stop-color: var(--svg-color--323232, #323232);
  stop-opacity: 0;
}

.jwb4ndb5j {
  stop-color: var(--svg-color--856152, #856152);
}

.jy2hb2y-z {
  stop-color: var(--svg-color--7e5658, #7E5658);
  stop-opacity: 0;
}

.k2ulk4b5g {
  stop-color: var(--svg-color--886150, #886150);
}

.k3zuzsc2p {
  stop-color: var(--svg-color--8a6154, #8A6154);
}

.knlj00b7g {
  d: path("M18.882 30H8.052l1.759-4.056a1.58 1.58 0 0 1 .87-.837a1.55 1.55 0 0 1 1.198.028l6.203 2.773a1.6 1.6 0 0 1 .821.885c.148.39.14.823-.02 1.207");
}

.kpv06y8mc {
  d: path("M29.759 7.44a.72.72 0 0 0-.624.483l-.997 2.878a.74.74 0 0 0-.029.404a.8.8 0 0 0 .19.372c.097.11.223.199.368.26c.145.062.306.094.468.094h.624z");
}

.kumz7j9en {
  stop-color: var(--svg-color--c7a7a3, #C7A7A3);
}

.kyixh_zyc {
  stop-color: var(--svg-color--5d2f2a, #5D2F2A);
}

.l3qsb7b0m {
  d: path("m18.656 26.342l-5.94-2.639a.5.5 0 0 0-.66.254l-.617 1.39a.5.5 0 0 0 .254.659l5.94 2.639a.5.5 0 0 0 .66-.254L18.91 27a.5.5 0 0 0-.254-.66");
}

.l6be9nb1o {
  stop-color: var(--svg-color--2b2a2c, #2B2A2C);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ly5mjubfm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M15.92 18.723c-.93 0-1.799.546-2.774 4.446");
}

.lzqapmb5m {
  stop-color: var(--svg-color--ac8ce9, #AC8CE9);
  stop-opacity: 0;
}

.m2qwe2bau {
  d: path("M27.658 7.57c0-.514-.417-.856-.53-.96l-.514.497l.316.644z");
}

.m39r3gb6m {
  stop-color: var(--svg-color--977eb0, #977EB0);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgsdx-idi {
  stop-color: var(--svg-color--8b605d, #8B605D);
}

.mk1v4mb7i {
  stop-color: var(--svg-color--7c4d52, #7C4D52);
  stop-opacity: 0;
}

.mkru76bzi {
  stop-color: var(--svg-color--7e62b9, #7E62B9);
}

.mpg30ebba {
  fill-rule: evenodd;
  d: path("M14.63 8.866a.85.85 0 0 1 .937.753a5.64 5.64 0 0 0 1.487 3.242a.85.85 0 0 1-1.242 1.161a7.35 7.35 0 0 1-1.935-4.219a.85.85 0 0 1 .753-.937");
}

.mqfkvh4ai {
  stop-color: var(--svg-color--946fe2, #946FE2);
  stop-opacity: 0;
}

.mtz5hyb1s {
  stop-color: var(--svg-color--9f7c71, #9F7C71);
}

.mwyzrubgp {
  stop-color: var(--svg-color--4b3f3f, #4B3F3F);
}

.n52mgrb1s {
  opacity: var(--svg-opacity--0-4, 0.4);
}

.naydt1bhx {
  stop-color: var(--svg-color--50366c, #50366C);
  stop-opacity: 0;
}

.njx-vzunm {
  stop-color: var(--svg-color--a27f74, #A27F74);
  stop-opacity: 0;
}

.nm7y5sbkv {
  stop-color: var(--svg-color--886150, #886150);
  stop-opacity: 0;
}

.nmsds2uhw {
  stop-color: var(--svg-color--5d2f2a, #5D2F2A);
  stop-opacity: 0;
}

.nn824ubqo {
  d: path("M21.759 11a2.75 2.75 0 1 0 0-5.5a2.75 2.75 0 0 0 0 5.5");
}

.o6p46_fol {
  stop-color: var(--svg-color--84496b, #84496B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh8xzh-ai {
  stop-color: var(--svg-color--7e5658, #7E5658);
}

.p_ppzwbju {
  fill: var(--svg-color--000, #000);
  d: path("M27.117 7.757a.906.906 0 0 0-.91-.91a.906.906 0 0 0-.91.91a.9.9 0 0 0 .101.419h1.61a.9.9 0 0 0 .109-.42");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqo3njvzl {
  stop-color: var(--svg-color--754159, #754159);
  stop-opacity: 0;
}

.pqpr8gbnv {
  stop-color: var(--svg-color--7e6a9f, #7E6A9F);
  stop-opacity: 0;
}

.pwogqrrxj {
  stop-color: var(--svg-color--210d2a, #210D2A);
  stop-opacity: 0;
}

.q1ytiebzb {
  stop-color: var(--svg-color--180614, #180614);
}

.qavb5353a {
  stop-color: var(--svg-color--180614, #180614);
  stop-opacity: 0;
}

.qpu8u57mt {
  stop-color: var(--svg-color--895656, #895656);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_zcvubtv {
  stop-color: var(--svg-color--7c4d52, #7C4D52);
}

.r0ayoebke {
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  d: path("M26.297 6.627c.09.171.045.38-.35.413a.36.36 0 0 0-.26.161c-.165.243-.382.163-.47-.002c-.103-.195.055-.48.353-.638s.624-.128.727.066");
}

.r4zlxac_f {
  stop-color: var(--svg-color--9c84d9, #9C84D9);
}

.r96zhabkz {
  stop-color: var(--svg-color--754444, #754444);
}

.ra9ofbb3d {
  stop-color: var(--svg-color--977eb0, #977EB0);
}

.riwrb4b-h {
  stop-color: var(--svg-color--612b3a, #612B3A);
  stop-opacity: 0;
}

.rmch-r34p {
  stop-color: var(--svg-color--8c6355, #8C6355);
}

.rw0bm_m_p {
  stop-color: var(--svg-color--754548, #754548);
  stop-opacity: 0;
}

.rw3jljcef {
  stop-color: var(--svg-color--926b58, #926B58);
  stop-opacity: 0;
}

.s16-0b09b {
  stop-color: var(--svg-color--8a5c4d, #8A5C4D);
  stop-opacity: 0;
}

.s30kpos8d {
  stop-color: var(--svg-color--8c6355, #8C6355);
  stop-opacity: 0;
}

.s38f0kzba {
  stop-color: var(--svg-color--8b6ba9, #8B6BA9);
}

.s4aq1wf1v {
  stop-color: var(--svg-color--813d50, #813D50);
}

.sa79bdt-x {
  stop-color: var(--svg-color--a27f74, #A27F74);
}

.slgrfcb7b {
  width: 2.859px;
  height: 8.147px;
  x: 21.294px;
  y: 13.466px;
  rx: 1.429px;
}

.smf4pibyk {
  d: path("M17.922 21.41c.598-1.607-.205-2.863-1.062-3.222c-1.038-.435-2.5-.086-3.149 1.414l.29 1.015l1.174-.512c.082-.035.167.048.137.132c-.64 1.789.252 2.099.642 2.287c.248.119 1.414.378 1.968-1.114");
}

.t4mvb7bzl {
  stop-color: var(--svg-color--743e56, #743E56);
}

.tepwdy0ri {
  stop-color: var(--svg-color--612b3a, #612B3A);
}

.u_g01gbit {
  stop-color: var(--svg-color--743c52, #743C52);
  stop-opacity: 0;
}

.u2kebkbsf {
  stop-color: var(--svg-color--754548, #754548);
}

.u6r-6abtn {
  stop-color: var(--svg-color--7b3d61, #7B3D61);
  stop-opacity: 0;
}

.ua0gepbrj {
  stop-color: var(--svg-color--754444, #754444);
  stop-opacity: 0;
}

.uom2sabkf {
  stop-color: var(--svg-color--8b6ba9, #8B6BA9);
  stop-opacity: 0;
}

.uprsnpi8o {
  stroke: var(--svg-color--d4d2dd, #D4D2DD);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.964 9.631c.143.831.67 2.716 1.633 3.61");
}

.v_4ryrg3h {
  stop-color: var(--svg-color--84496b, #84496B);
  stop-opacity: 0;
}

.v0tqkfbzj {
  stop-color: var(--svg-color--4b3f3f, #4B3F3F);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6p9ujc-q {
  d: path("M18.547 2h11.212v17h-7.643a5.35 5.35 0 0 1-5.357-5.357c0-.843.202-1.634.539-2.342a.86.86 0 0 0 0-.758a5.6 5.6 0 0 1-.54-2.375c0-1.126.336-2.152.907-3.026l.003-.007a5.4 5.4 0 0 0 .876-2.948V2.17q0-.085.003-.17");
}

.vixtmqora {
  stop-color: var(--svg-color--978ca5, #978CA5);
}

.vmv1chbop {
  fill: var(--svg-color--463636, #463636);
  d: path("M18.547 2h11.212v17h-7.643a5.35 5.35 0 0 1-5.357-5.357c0-.843.202-1.634.539-2.342a.86.86 0 0 0 0-.758a5.6 5.6 0 0 1-.54-2.375c0-1.126.336-2.152.907-3.026l.003-.007a5.4 5.4 0 0 0 .876-2.948V2.17q0-.085.003-.17");
}

.vnl9t5uuk {
  fill: var(--svg-color--996562, #996562);
  d: path("m19.282 25.914l-.485.922l-6.656-2.5c.052-.255.222-.994.485-1.906c.262-.913.843-2.328 1.14-2.953l6.64 2.187l.737-1.37a1.498 1.498 0 0 1 2.22-.487c.66.495.794 1.43.289 2.083c-.361.466-.76.97-1.105 1.383c-.87 1.045-1.64 1.454-2.297 1.75a2.23 2.23 0 0 0-.968.891");
}

.vwnsgewhv {
  stop-color: var(--svg-color--6f4238, #6F4238);
}

.vzfqaisso {
  stop-color: var(--svg-color--845b51, #845B51);
  stop-opacity: 0;
}

.w24p3s3hz {
  stop-color: var(--svg-color--85495e, #85495E);
  stop-opacity: 0;
}

.w3m8-rhdb {
  stop-color: var(--svg-color--885b4c, #885B4C);
  stop-opacity: 0;
}

.wf6f59y-w {
  stop-color: var(--svg-color--85534f, #85534F);
}

.wj-6zublk {
  stop-color: var(--svg-color--9c7563, #9C7563);
}

.wvoeu8l0f {
  stop-color: var(--svg-color--957db3, #957DB3);
}

.x6ndepp5s {
  stop-color: var(--svg-color--885b4c, #885B4C);
}

.x9qs5h_6z {
  stop-color: var(--svg-color--926cdc, #926CDC);
}

.xa036tbdv {
  fill: var(--svg-color--1f1e1e, #1F1E1E);
  fill-rule: evenodd;
  d: path("M26.584 4.026a4.3 4.3 0 0 0-2.592.429a.505.505 0 0 1-.676-.206a.485.485 0 0 1 .21-.662a5.32 5.32 0 0 1 3.207-.53c.273.04.461.29.42.557a.5.5 0 0 1-.569.412");
}

.xg5e2ibba {
  stop-color: var(--svg-color--8c6ad7, #8C6AD7);
}

.y2cwqjbez {
  stop-color: var(--svg-color--7c5344, #7C5344);
  stop-opacity: 0;
}

.y6hhg3cco {
  stop-color: var(--svg-color--7c3b73, #7C3B73);
}

.yc0ivbchf {
  d: path("M26.207 6.168a1.59 1.59 0 0 0-1.532 2.008h3.07c.036-.138.058-.275.058-.42a1.6 1.6 0 0 0-1.596-1.588");
}

.yf5xvlbkn {
  stop-color: var(--svg-color--7f5dbc, #7F5DBC);
}

.zas4czo7h {
  stop-color: var(--svg-color--9c84d9, #9C84D9);
  stop-opacity: 0;
}

.zjbt99bun {
  stop-color: var(--svg-color--734147, #734147);
}

.zpdkuubmz {
  stop-color: var(--svg-color--7e475c, #7E475C);
}

</style>
