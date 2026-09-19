<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iinGR8c)"><path class="td6euhb6l"/></g><path fill="url(#itsSeme)" class="i6tnjcu8m"/><g filter="url(#izvDE3c)"><path fill="url(#icQ8Rgb)" class="if2-x0_3s"/></g><path fill="url(#iNy3SEd)" class="x5s8xacrq"/><g filter="url(#i77DFid)"><path fill="url(#i3c3asc)" class="juibrfwbj"/></g><path fill="url(#iQ1GUZp)" class="juibrfwbj"/><g filter="url(#i7Aw7hD)"><path class="oo5c6lzng"/></g><path fill="url(#ibotHnd)" class="gejm97-ji"/><path fill="url(#ikosdOb)" class="gejm97-ji"/><g filter="url(#i4LuPpd)"><path fill="url(#iQPSHxS)" class="yr50mjbls"/></g><path class="dtw7czlgj"/><path fill="url(#ifXi0Wc)" class="c4xzopb1o"/><path fill="url(#ik1cyde)" class="c4xzopb1o"/><path fill="url(#iJZk41c)" class="c4xzopb1o"/><path fill="url(#ilZrQJe)" class="km_8uqbsr"/><path fill="url(#ipnDrwc)" class="km_8uqbsr"/><path fill="url(#iXzNVpd)" class="ifesvnbka"/><path fill="url(#itapmge)" class="ifesvnbka"/><g filter="url(#ik2XoHe)"><path fill="url(#iBzQPme)" class="pnx4wsrrl"/></g><path fill="url(#iIY0Aje)" class="pnx4wsrrl"/><path fill="url(#iIePIbe)" class="pnx4wsrrl"/><path fill="url(#iMpooEc)" class="pnx4wsrrl"/><g filter="url(#iAGhILc)"><path class="y1z1vonft"/></g><g filter="url(#iNMFlBc)"><path fill="url(#iqGgBpd)" class="ulx2x9bfe"/><path fill="url(#i85Fsmb)" class="ulx2x9bfe"/><path fill="url(#isNmgZc)" class="ulx2x9bfe"/><path fill="url(#ie2Q6Ke)" class="ulx2x9bfe"/></g><path fill="url(#iO8yJXc)" class="viukjevqq"/><g filter="url(#iTKQtfe)"><path fill="url(#i7Dgu6b)" class="q04qidcke"/><path fill="url(#iN9aaum)" class="q04qidcke"/><path fill="url(#iCPqzEd)" class="q04qidcke"/><path fill="url(#iVANHNd)" class="q04qidcke"/><path fill="url(#i78UPMb)" class="q04qidcke"/></g><g filter="url(#iui99nb)"><path class="zdhfb1sod"/></g><g filter="url(#ixkgMHc)"><path class="dl8hm0inq"/></g><g filter="url(#i5bQP8D)"><path fill="url(#i9tNhGe)" class="kt5ibs3iw"/><path fill="url(#iCOPVGu)" class="kt5ibs3iw"/></g><g filter="url(#iluVt8b)"><path fill="url(#irwpH9d)" class="hhb5bbbzw"/><path fill="url(#iRYSQjb)" class="hhb5bbbzw"/><path fill="url(#irnrBHe)" class="hhb5bbbzw"/><path fill="url(#ixLycIn)" class="hhb5bbbzw"/></g><path class="pck9pabxc"/><path fill="url(#iJZutVv)" class="jyu3lwbui"/><path class="ie_ridc7a"/><g filter="url(#iowZDCe)"><path class="hn5cgubhu"/><path fill="url(#iuFGCZb)" class="e8gwilb4t"/></g><g filter="url(#iu2F1mK)"><path fill="url(#iqhSnae)" class="y826rog8t"/></g><path class="wtcnn1bts"/><path fill="url(#iT8yY8d)" class="mqmfq5v9o"/><path class="dtfbqac-i"/><g filter="url(#i2lKIUc)"><path fill="url(#iHecyFb)" class="gvwznf_ar"/></g><g filter="url(#iHToxrd)"><ellipse transform="rotate(-27.914 16.124 6.566)" class="tav86hd_q"/><ellipse fill="url(#iiNWFod)" transform="rotate(-27.914 16.124 6.566)" class="ru1di9zea"/></g><path fill="url(#im6HbWz)" class="ukvl8u6wk"/><path fill="url(#i0caq2l)" class="ukvl8u6wk"/><path fill="url(#iRsJ1xd)" class="ukvl8u6wk"/><path fill="url(#iuOr7zd)" class="h5cqi1vlg"/><path fill="url(#ijQ8VFd)" class="h5cqi1vlg"/><g filter="url(#iozuoFd)"><path class="obm0x2_ia"/></g><g filter="url(#ieSLevb)"><path class="es1-dkbsg"/></g><g filter="url(#iRnUmGW)"><path class="oyplvmbvn"/></g><g filter="url(#iFJZfMq)"><path class="c1f0lfkgq"/></g><g filter="url(#i4634Ie)"><path fill="url(#i5hBc1c)" class="uwupv_ztt"/><path fill="url(#iskeGDX)" class="uwupv_ztt"/></g><path fill="url(#iYcj16d)" class="uwupv_ztt"/><path fill="url(#iZqERtb)" class="uwupv_ztt"/><g filter="url(#iyhIzKe)"><path stroke="url(#iFIIACe)" class="izop3bc_a"/></g><g filter="url(#iPkphGp)"><path stroke="url(#iFh5wUb)" class="xwn-kfb_d"/></g><g filter="url(#icj0I2b)"><path stroke="url(#iUCaIqe)" class="w-8ib2bba"/></g><defs><radialGradient id="itsSeme" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 87.822 -23.113)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="icQ8Rgb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 22.702 20.617)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="iNy3SEd" cx="0" cy="0" r="1" gradientTransform="matrix(.67968 -.9375 .55678 .40367 6.762 16.945)" gradientUnits="userSpaceOnUse"><stop class="mkkd392fx"/><stop offset="1" class="uukk9e6th"/></radialGradient><radialGradient id="iQ1GUZp" cx="0" cy="0" r="1" gradientTransform="matrix(-1.89062 1.84376 -.54832 -.56226 14.3 14.241)" gradientUnits="userSpaceOnUse"><stop class="wgh8neb9i"/><stop offset="1" class="jatq7acdd"/></radialGradient><radialGradient id="ibotHnd" cx="0" cy="0" r="1" gradientTransform="matrix(3.0625 1.53125 -.77813 1.55625 20.708 13.695)" gradientUnits="userSpaceOnUse"><stop class="jmmt11xfr"/><stop offset="1" class="z7xjq9sfn"/></radialGradient><radialGradient id="ikosdOb" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 2.78125 -.88036 .22751 23.786 10.804)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="cz5ixmbyk"/><stop offset="1" class="zuudtxbmr"/></radialGradient><radialGradient id="iQPSHxS" cx="0" cy="0" r="1" gradientTransform="matrix(-.68567 .5 -.27415 -.37595 25.691 7.492)" gradientUnits="userSpaceOnUse"><stop class="ts5vg6ilu"/><stop offset="1" class="pltv3850l"/></radialGradient><radialGradient id="ifXi0Wc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.89062 2.15625 -2.03255 -2.7248 17.192 9.788)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="gceicvbbq"/><stop offset="1" class="aams3y-6i"/></radialGradient><radialGradient id="ik1cyde" cx="0" cy="0" r="1" gradientTransform="rotate(-169.33 10.038 5.616)scale(1.48709 1.90039)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="slf3m1bsw"/><stop offset="1" class="w62bkkgyk"/></radialGradient><radialGradient id="iJZk41c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.35937 -1.53125 0 19.786 10.695)" gradientUnits="userSpaceOnUse"><stop class="xsdey3bnk"/><stop offset="1" class="w4b405bhh"/></radialGradient><radialGradient id="ilZrQJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.50057 2.1394 -2.54146 -.59464 20.716 7.687)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="ipnDrwc" cx="0" cy="0" r="1" gradientTransform="matrix(.16832 .23084 -.1961 .14299 20.288 7.84)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iXzNVpd" cx="0" cy="0" r="1" gradientTransform="matrix(.76496 2.25141 -1.02337 .34771 14.348 7.754)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="itapmge" cx="0" cy="0" r="1" gradientTransform="matrix(.18275 .57228 -.50201 .1603 14.728 7.75)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iBzQPme" cx="0" cy="0" r="1" gradientTransform="matrix(-2.99992 0 0 -5.40698 19.143 7.147)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iIY0Aje" cx="0" cy="0" r="1" gradientTransform="matrix(-.57059 4.92453 -5.1393 -.59547 18.13 5.913)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="yscqqhbxi"/><stop offset=".984" class="pjd00uw_b"/></radialGradient><radialGradient id="iIePIbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.81132 .97679 0 16.332 6.47)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iMpooEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.88097 1.14265 0 18.96 6.233)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iO8yJXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.41358 1.66395 0 17.532 9.177)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iN9aaum" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.28174 5.8146 0 14.531 6.239)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iCPqzEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.08454 3.69339 0 20.321 6.239)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iVANHNd" cx="0" cy="0" r="1" gradientTransform="rotate(-160.666 10.169 -.375)scale(2.49729 1.32998)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="i78UPMb" cx="0" cy="0" r="1" gradientTransform="matrix(.51938 .8464 -1.95987 1.20265 17.013 1.723)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="i9tNhGe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18454 .7882 -.21938 -.608 17.678 2.551)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iCOPVGu" cx="0" cy="0" r="1" gradientTransform="matrix(1.8467 -2.92394 3.23942 2.04595 14.416 5.282)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="irwpH9d" cx="0" cy="0" r="1" gradientTransform="matrix(1.94288 .45954 -.257 1.08659 19.61 3.217)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iRYSQjb" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 11.925 -2.967)scale(2.45705 1.37028)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="irnrBHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.7502 -1.26375 .90517 -.53734 20.12 5.687)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="ixLycIn" cx="0" cy="0" r="1" gradientTransform="matrix(-2.7535 .6606 -.71413 -2.97664 20.283 3.15)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="iJZutVv" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46556 -.74053 0 18.784 6.62)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iuFGCZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.13284 -.17118 .23568 -.1829 18.653 6.67)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iT8yY8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46559 -.74057 0 16.28 6.62)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iiNWFod" cx="0" cy="0" r="1" gradientTransform="matrix(-.00443 -.283 .34019 -.00533 16.115 6.746)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0caq2l" cx="0" cy="0" r="1" gradientTransform="matrix(.36068 1.28726 -1.22815 .34412 20.182 6.629)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iRsJ1xd" cx="0" cy="0" r="1" gradientTransform="matrix(.45206 -.62037 .52 .37891 20.389 6.941)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="ijQ8VFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23692 1.19129 -1.17115 -.23291 14.512 6.725)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="i5hBc1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.46875 -5.71107 0 19.177 12.742)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="dw0qvsbps"/><stop offset="1" class="yafg_whjr"/></radialGradient><radialGradient id="iskeGDX" cx="0" cy="0" r="1" gradientTransform="rotate(58.499 -1.805 23.135)scale(1.85402 1.92266)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="pygktylau"/><stop offset="1" class="dqd47gnac"/></radialGradient><radialGradient id="iZqERtb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.00003 -7.0781 9.3879 -5.30536 19.333 16.96)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="gv9be6ybc"/><stop offset="1" class="nqt5hcbes"/></radialGradient><filter id="iinGR8c" width="16.97" height="13.626" x="7.639" y="16.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1287"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1287" result="effect2_innerShadow_4002_1287"/></filter><filter id="izvDE3c" width="8.803" height="12.453" x="15.083" y="15.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".5"/></filter><filter id="i77DFid" width="9.329" height="6.572" x="5.433" y="10.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.611765 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1287"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.509804 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1287" result="effect2_innerShadow_4002_1287"/></filter><filter id="i7Aw7hD" width="5.98" height="8.393" x="20.337" y="7.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.529412 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1287"/></filter><filter id="i4LuPpd" width="1.41" height="1.949" x="24.485" y="7.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.607843 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1287"/></filter><filter id="ik2XoHe" width="6.015" height="7.082" x="14.627" y="3.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1287"/></filter><filter id="iAGhILc" width="3.077" height="3.664" x="15.874" y="5.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".5"/></filter><filter id="iNMFlBc" width="1.277" height="1.864" x="16.894" y="6.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".05"/></filter><filter id="iTKQtfe" width="7.387" height="5.008" x="13.839" y="1.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1287"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1287" result="effect2_innerShadow_4002_1287"/></filter><filter id="iui99nb" width="1.385" height=".768" x="18.444" y="4.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1287"/></filter><filter id="ixkgMHc" width="1.385" height=".76" x="15.428" y="4.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1287"/></filter><filter id="i5bQP8D" width="3.691" height="3.344" x="14.086" y="2.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".05"/></filter><filter id="iluVt8b" width="3.582" height="3.224" x="17.465" y="2.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".05"/></filter><filter id="iowZDCe" width=".536" height=".484" x="18.32" y="6.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".05"/></filter><filter id="iu2F1mK" width=".681" height=".694" x="18.759" y="6.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".1"/></filter><filter id="i2lKIUc" width=".736" height=".767" x="16.21" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".1"/></filter><filter id="iHToxrd" width=".608" height=".489" x="15.82" y="6.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".05"/></filter><filter id="iozuoFd" width=".776" height="1.378" x="14.064" y="6.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".075"/></filter><filter id="ieSLevb" width=".843" height="1.392" x="20.229" y="6.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".075"/></filter><filter id="iRnUmGW" width="1.25" height=".535" x="15.446" y="5.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".05"/></filter><filter id="iFJZfMq" width="1.25" height=".535" x="18.476" y="5.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".05"/></filter><filter id="i4634Ie" width="6.555" height="7.624" x="14.255" y="10.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.470588 0 0 0 0 0.0117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1287"/></filter><filter id="iyhIzKe" width="11.112" height="3.615" x="10.829" y="25.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".2"/></filter><filter id="iPkphGp" width="3.297" height="3.17" x="8.245" y="23.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".2"/></filter><filter id="icj0I2b" width="3.085" height="3.032" x="11.506" y="23.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1287" stdDeviation=".2"/></filter><linearGradient id="i3c3asc" x1="8.177" x2="13.645" y1="16.679" y2="13.429" gradientUnits="userSpaceOnUse"><stop class="t202zjbmo"/><stop offset="1" class="rp-p5iblf"/></linearGradient><linearGradient id="iqGgBpd" x1="17.532" x2="18.023" y1="7.622" y2="7.622" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="i85Fsmb" x1="16.917" x2="17.533" y1="7.533" y2="7.567" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="isNmgZc" x1="17.532" x2="17.532" y1="7.851" y2="8.34" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="ie2Q6Ke" x1="17.532" x2="17.532" y1="6.561" y2="6.802" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="i7Dgu6b" x1="20.61" x2="14.8" y1="3.897" y2="3.897" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iqhSnae" x1="19.23" x2="19.05" y1="6.652" y2="6.762" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHecyFb" x1="16.706" x2="16.526" y1="6.651" y2="6.762" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="im6HbWz" x1="21.226" x2="20.533" y1="6.667" y2="7.916" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iuOr7zd" x1="14.175" x2="15.012" y1="7.071" y2="6.998" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iYcj16d" x1="13.802" x2="15.755" y1="16.085" y2="16.085" gradientUnits="userSpaceOnUse"><stop class="x8wsft-hb"/><stop offset="1" class="m0mihob_v"/></linearGradient><linearGradient id="iFIIACe" x1="11.768" x2="20.875" y1="27.015" y2="28.857" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iFh5wUb" x1="10.518" x2="8.203" y1="25.808" y2="25.435" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iUCaIqe" x1="14.013" x2="13.482" y1="24.145" y2="26.255" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-merpeople" /></template>
<style>
.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.aams3y-6i {
  stop-color: var(--svg-color--f6a510, #F6A510);
  stop-opacity: 0;
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c1f0lfkgq {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.575 5.508a1.33 1.33 0 0 0-.95-.219");
}

.c4xzopb1o {
  d: path("M19.864 10.562c-2.102-.57-3.82-.266-4.656 0v3.32h4.656z");
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.cz5ixmbyk {
  stop-color: var(--svg-color--eba238, #EBA238);
}

.dl8hm0inq {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M15.575 5.374a1.6 1.6 0 0 1 .998-.206a.16.16 0 1 1-.039.316a1.27 1.27 0 0 0-.839.19l-.01.007v.002a.16.16 0 0 1-.196-.252z");
}

.dqd47gnac {
  stop-color: var(--svg-color--ff8e3e, #FF8E3E);
  stop-opacity: 0;
}

.dtfbqac-i {
  fill: var(--svg-color--000, #000);
  d: path("M16.572 6.86a.29.29 0 0 0-.293-.294a.292.292 0 0 0-.261.428h.52a.3.3 0 0 0 .034-.135");
}

.dtw7czlgj {
  fill: var(--svg-color--ffc028, #FFC028);
  d: path("M19.864 10.562c-2.102-.57-3.82-.266-4.656 0v3.32h4.656z");
}

.dw0qvsbps {
  stop-color: var(--svg-color--ff8738, #FF8738);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e8gwilb4t {
  d: path("M18.747 6.456c.037.048-.04.108-.126.172c-.087.065-.151.11-.187.062c-.037-.049.004-.14.09-.205c.087-.065.187-.078.223-.03");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.es1-dkbsg {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("m20.38 7.543l.063-1.093a.548.548 0 0 1-.064 1.093");
}

.ft5dv1b6b {
  fill: none;
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gceicvbbq {
  stop-color: var(--svg-color--c47001, #C47001);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gejm97-ji {
  d: path("m23.587 12.28l-2.844-1.464l-.406 2.718l3.348 1.708a1.8 1.8 0 0 0 1.84-.121c.527-.363.82-.979.79-1.618c-.06-1.273-.081-2.688-.103-3.586v-1.39a.531.531 0 0 0-1.063 0v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.667a.531.531 0 1 0-1.062 0v1.201a1 1 0 0 0 .235.644l.373.444a.2.2 0 0 1 .046.151c-.065.582-.148 1.353-.197 1.853a.202.202 0 0 1-.293.16");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gv9be6ybc {
  stop-color: var(--svg-color--e15c10, #E15C10);
  stop-opacity: 0;
}

.gvwznf_ar {
  d: path("M16.746 6.798c0-.165-.134-.275-.17-.308l-.166.16l.102.207z");
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h5cqi1vlg {
  d: path("M14.632 6.08a.924.924 0 0 0 .08 1.836a45 45 0 0 1-.08-1.836");
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.hhb5bbbzw {
  d: path("m20.523 5.86l-.017-.363a.843.843 0 0 0-.806-.818h-.803a1.39 1.39 0 0 1-1.22-.723s-.055-.128-.098-.337c-.1-.491.359-.858.853-.77c.587.103 1.286.296 1.792.626c1.001.653.826 1.83.3 2.384");
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hn5cgubhu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.747 6.456c.037.048-.04.108-.126.172c-.087.065-.151.11-.187.062c-.037-.049.004-.14.09-.205c.087-.065.187-.078.223-.03");
}

.i6tnjcu8m {
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ie_ridc7a {
  fill: var(--svg-color--000, #000);
  d: path("M18.492 6.86c0-.164.13-.294.293-.294a.292.292 0 0 1 .261.428h-.52a.3.3 0 0 1-.034-.135");
}

.if2-x0_3s {
  d: path("M21.317 26.71c0-5.343-3.922-7.968-5.234-9l3.25-1.453c1.125.521 3.035 2.358 3.453 5.11c.484 3.187-.927 4.927-1.469 5.343");
}

.ifesvnbka {
  d: path("M14.743 7.864a.94.94 0 0 1-.52-.177v.534c0 .512.306.969.77 1.158a2.4 2.4 0 0 1-.199-.677z");
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.izop3bc_a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.429 26.909c-.007.65.436 1.948 2.266 1.948h3.177c1.01-.014 3.317-.516 4.469-2.414");
}

.jatq7acdd {
  stop-color: var(--svg-color--e68c1f, #E68C1F);
  stop-opacity: 0;
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jmmt11xfr {
  stop-color: var(--svg-color--df7837, #DF7837);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.juibrfwbj {
  d: path("m6.569 15.067l-.755.857a.526.526 0 0 0 .776.71l.554-.583a.384.384 0 0 1 .476-.065l.018.01a.1.1 0 0 1 .019.155l-.317.316a.528.528 0 0 0 .716.774l.613-.527h1.839a2.5 2.5 0 0 0 1.64-.613l2.365-2.055v-3.25c-.257.025-.59.285-.723.418l-3.247 3.04a.5.5 0 0 1-.284.132l-3.068.355a.98.98 0 0 0-.622.326");
}

.jyu3lwbui {
  d: path("M18.785 6.347a.512.512 0 0 1 .494.647h-.99a.514.514 0 0 1 .496-.647");
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.km_8uqbsr {
  d: path("M20.322 7.864a.94.94 0 0 0 .519-.177v.534c0 .512-.306.969-.77 1.158q.147-.312.199-.677z");
}

.kt5ibs3iw {
  d: path("m17.666 3.924l-.038-.078a.38.38 0 0 0-.353-.24h-.73c-1.06 0-1.918.868-1.918 1.939v.158c-.195-.149-.44-.462-.44-.969c0-.615.448-.926.734-1.124c.08-.056.149-.103.19-.146l.057-.06c.2-.212.558-.591 1.182-.757a3 3 0 0 1 .52-.086c.471-.036.808.376.808.85v.505z");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m0mihob_v {
  stop-color: var(--svg-color--fb711e, #FB711E);
  stop-opacity: 0;
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mkkd392fx {
  stop-color: var(--svg-color--d69b3c, #D69B3C);
}

.mqmfq5v9o {
  d: path("M16.279 6.347a.512.512 0 0 0-.494.647h.99a.516.516 0 0 0-.496-.647");
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nqt5hcbes {
  stop-color: var(--svg-color--e15c10, #E15C10);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.obm0x2_ia {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M14.642 6.46a.548.548 0 0 0 .048 1.078a45 45 0 0 1-.048-1.079");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oo5c6lzng {
  fill: var(--svg-color--ffca36, #FFCA36);
  d: path("m23.587 12.28l-2.844-1.464l-.406 2.718l3.348 1.708a1.8 1.8 0 0 0 1.84-.121c.527-.363.82-.979.79-1.618c-.06-1.273-.081-2.688-.103-3.586v-1.39a.531.531 0 0 0-1.063 0v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.667a.531.531 0 1 0-1.062 0v1.201a1 1 0 0 0 .235.644l.373.444a.2.2 0 0 1 .046.151c-.065.582-.148 1.353-.197 1.853a.202.202 0 0 1-.293.16");
}

.oyplvmbvn {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.596 5.535c.148-.106.515-.292.95-.22");
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pck9pabxc {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.904 6.191c.375 0 .691.258.778.608a.157.157 0 0 1-.154.195h-1.28a.132.132 0 0 1-.13-.156a.8.8 0 0 1 .786-.647");
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pjd00uw_b {
  stop-color: var(--svg-color--da8723, #DA8723);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pltv3850l {
  stop-color: var(--svg-color--f3ae26, #F3AE26);
}

.pnx4wsrrl {
  d: path("M14.763 8.733a2.25 2.25 0 0 0 2.23 1.955h1.083a2.25 2.25 0 0 0 2.23-1.955c.067-1.08.135-2.157.185-3.238a.83.83 0 0 0-.79-.821h-.804a1.39 1.39 0 0 1-1.27-.828a.38.38 0 0 0-.352-.24h-.73c-1.06 0-1.918.868-1.918 1.939c0 1.067.066 2.118.136 3.188");
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.pygktylau {
  stop-color: var(--svg-color--ff8e3e, #FF8E3E);
}

.q04qidcke {
  d: path("M20.318 3.335c.295.101.56.307.727.603a1.36 1.36 0 0 1-.06 1.45a.9.9 0 0 0-.156.501v.682a1 1 0 0 0-.383-.154l.045-.922a.83.83 0 0 0-.79-.821h-.804a1.39 1.39 0 0 1-1.27-.828a.38.38 0 0 0-.353-.24h-.73c-1.06 0-1.917.867-1.917 1.939l.017.882a1 1 0 0 0-.413.151V5.89a.9.9 0 0 0-.155-.501a1.37 1.37 0 0 1-.083-1.404c.168-.317.439-.539.746-.646c.329-.117.609-.339.794-.637a1.334 1.334 0 0 1 1.66-.524a.85.85 0 0 0 .684 0a1.334 1.334 0 0 1 1.665.542c.176.293.453.505.776.616");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rp-p5iblf {
  stop-color: var(--svg-color--fdb332, #FDB332);
}

.ru1di9zea {
  cx: 16.124px;
  cy: 6.566px;
  rx: 0.223px;
  ry: 0.113px;
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.slf3m1bsw {
  stop-color: var(--svg-color--ffc724, #FFC724);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.t202zjbmo {
  stop-color: var(--svg-color--ffba30, #FFBA30);
}

.tav86hd_q {
  cx: 16.124px;
  cy: 6.566px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.223px;
  ry: 0.113px;
}

.td6euhb6l {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
}

.ts5vg6ilu {
  stop-color: var(--svg-color--fccb44, #FCCB44);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.ukvl8u6wk {
  d: path("M20.356 7.916q.058-.915.106-1.831a.924.924 0 0 1-.106 1.831");
}

.ulx2x9bfe {
  d: path("m17.313 6.736l-.305 1.055c-.062.217.087.434.299.434h.45c.212 0 .362-.22.3-.434l-.305-1.055c-.066-.233-.37-.233-.44 0");
}

.uukk9e6th {
  stop-color: var(--svg-color--cf841f, #CF841F);
}

.uwupv_ztt {
  d: path("M14.255 10.891c0-.039.022-.074.058-.09c.2-.089.63-.262 1.09-.346a.05.05 0 0 1 .058.049v.778a2.054 2.054 0 1 0 4.107 0v-.778a.05.05 0 0 1 .058-.05c.462.085.92.259 1.125.348c.036.015.058.05.058.09v6.386a.6.6 0 0 1-.6.6h-5.354a.6.6 0 0 1-.6-.6z");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.viukjevqq {
  d: path("M17.532 8.809c-.291 0-.565-.069-.795-.189c-.078-.04-.163.049-.113.12c.192.291.527.486.908.486c.382 0 .717-.195.909-.486c.05-.074-.035-.16-.114-.12c-.23.12-.5.189-.795.189");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.w-8ib2bba {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.991 23.955c-.307.353-1.133 1.1-1.885 1.832");
}

.w4b405bhh {
  stop-color: var(--svg-color--fec026, #FEC026);
  stop-opacity: 0;
}

.w62bkkgyk {
  stop-color: var(--svg-color--ffc724, #FFC724);
  stop-opacity: 0;
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wgh8neb9i {
  stop-color: var(--svg-color--cc6124, #CC6124);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wtcnn1bts {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.16 6.191a.8.8 0 0 0-.777.608c-.026.1.05.195.153.195h1.28a.132.132 0 0 0 .131-.156a.804.804 0 0 0-.787-.647");
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x5s8xacrq {
  d: path("M6.762 16.087a.486.486 0 0 1 .973 0v.775a.486.486 0 1 1-.973 0z");
}

.x8wsft-hb {
  stop-color: var(--svg-color--db6229, #DB6229);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xsdey3bnk {
  stop-color: var(--svg-color--e89a05, #E89A05);
}

.xwn-kfb_d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.845 24.474c.41.162 1.402.783 2.096 1.97");
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y1z1vonft {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m17.253 6.849l-.364 1.055c-.062.217.087.434.299.434h.45c.212 0 .362-.22.3-.434l-.305-1.055c-.066-.234-.311-.234-.38 0");
}

.y826rog8t {
  d: path("M19.24 6.791a.5.5 0 0 0-.132-.265l-.149.164l.068.13z");
}

.yafg_whjr {
  stop-color: var(--svg-color--eb6820, #EB6820);
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yr50mjbls {
  d: path("M25.683 7.995h-.003a.53.53 0 0 0-.53.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.24-.2c-.124-.129-.169-.309-.169-.488V7.95l.56-.558a.44.44 0 0 1 .638.604");
}

.yscqqhbxi {
  stop-color: var(--svg-color--f7a229, #F7A229);
  stop-opacity: 0;
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.z7xjq9sfn {
  stop-color: var(--svg-color--ffaf2e, #FFAF2E);
  stop-opacity: 0;
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zdhfb1sod {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M19.674 5.437c-.1-.088-.217-.18-.394-.236c-.175-.055-.394-.07-.696-.033a.16.16 0 1 0 .039.316c.276-.034.445-.016.561.02c.114.036.19.094.281.173a.16.16 0 1 0 .21-.24");
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.zuudtxbmr {
  stop-color: var(--svg-color--eba238, #EBA238);
  stop-opacity: 0;
}

</style>
