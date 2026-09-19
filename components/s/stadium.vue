<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="ixS8cwe" class="ibvsa_2cr"/></defs><g class="ft5dv1b6b"><path fill="url(#iNV59Nd)" class="x6yiklbhx"/><path fill="url(#iXMXOdb)" class="x6yiklbhx"/><path fill="url(#iB2wMGc)" class="nq0adpaug"/><path fill="url(#iV7v0Sc)" class="nq0adpaug"/><path fill="url(#ipkqRnb)" class="gxr7nacaj"/><path fill="url(#imEVkQe)" class="gxr7nacaj"/><path fill="url(#i4jcFAe)" class="cacou6b3s"/><path fill="url(#i9ia15T)" class="cacou6b3s"/><path fill="url(#io0TOxe)" class="a8h6vacfd"/><path fill="url(#iy5fX4b)" class="a8h6vacfd"/><path fill="url(#iu6macd)" class="ja-liqbdz"/><path fill="url(#ifTtKsd)" class="ja-liqbdz"/><path fill="url(#ibOofHd)" class="l4n1dqaem"/><path fill="url(#ibBqwmd)" class="l4n1dqaem"/><path fill="url(#iecwobu)" class="l4n1dqaem"/><path fill="url(#iPg8tBb)" class="l4n1dqaem"/><g filter="url(#iVc8XKd)"><path fill="url(#ihK8Qkd)" class="t3rsy_bwp"/></g><g filter="url(#i5hNVnu)"><path fill="url(#ivjITzd)" class="upxj7db1i"/></g><g filter="url(#iK9X3Ce)"><path fill="url(#i2DiICe)" class="zr2rkmfgv"/></g><g filter="url(#iLWSWxz)"><path fill="url(#iQEffLc)" class="wcv_bnbjh"/></g><g filter="url(#ijVX16b)"><path fill="url(#i77AHOc)" class="p8oyfrbqf"/></g><g filter="url(#i1Zw7ye)"><path fill="url(#ijJ1kae)" class="fjvcgupkr"/></g><g filter="url(#iuOtTBb)"><path fill="url(#iowHfVg)" class="waw1jabny"/></g><g filter="url(#i5QDr2d)"><path fill="url(#iLPrbqQ)" class="g-ff56f6c"/></g><path fill="url(#iN0qaqd)" class="zhfi9sqka"/><g filter="url(#iLiPakV)"><path class="us5o8sbqa"/></g><g filter="url(#ieS68jc)"><path class="gxsqe_b3r"/></g><g filter="url(#iNHCU1z)"><path class="p2om2ur3c"/><path fill="url(#iU1sTdb)" class="ni0d10bhc"/></g><g filter="url(#iQ8hdOS)"><path class="nclx1-4lb"/></g><g filter="url(#ilOKSwE)"><path class="c725cyvoy"/></g><g filter="url(#ihPN8Hb)"><path class="dncv_tyrt"/><path fill="url(#ihoYoTd)" class="damd2ry4j"/></g><path fill="url(#iE3EIGA)" class="utckpdtss"/><path fill="url(#ioRtTuc)" class="hwn2b0b0z"/><path fill="url(#iWaNZEd)" class="int5dybyp"/><path fill="url(#ix9jfxc)" class="lxpy9kb1h"/><path fill="url(#i6AeWpd)" class="s60dpoulj"/><path fill="url(#i8d8vKe)" class="kpdjb8zuf"/><g filter="url(#iiodeTc)"><path class="xeo7t_l0i"/></g><g filter="url(#i2vsYPc)"><path class="japjmjpsm"/></g><g filter="url(#isMCGgd)"><use href="#ixS8cwe"/></g><g filter="url(#isMCGgd)"><use href="#ixS8cwe"/><path fill="url(#iixfplb)" class="cowxu0sqh"/></g><path fill="url(#iVOcJyp)" class="cowxu0sqh"/><g filter="url(#iGZhIDc)"><path class="n8ozs5pyu"/></g><path fill="url(#in7BF2G)" class="mno310bpx"/><path fill="url(#iOsgFob)" class="bow9bs5yu"/><g filter="url(#iQwYtTb)"><path stroke="url(#iJjH6hs)" class="x2wudq_vz"/></g><g filter="url(#ioVHhcc)"><path stroke="url(#ieDCMxb)" class="efz0mebro"/></g><g filter="url(#ib5PLhb)"><path stroke="url(#imprwCe)" class="sdqjcrdtt"/></g><defs><linearGradient id="iNV59Nd" x1="12.617" x2="11.823" y1="14.126" y2="14.126" gradientUnits="userSpaceOnUse"><stop class="k7ht9rb5w"/><stop offset=".889" class="nr1zmhoko"/></linearGradient><linearGradient id="iXMXOdb" x1="13.096" x2="12.829" y1="12.983" y2="13.697" gradientUnits="userSpaceOnUse"><stop class="vdcy8-rqm"/><stop offset="1" class="s5qq57b7i"/></linearGradient><linearGradient id="iB2wMGc" x1="3.673" x2="2.896" y1="14.326" y2="14.326" gradientUnits="userSpaceOnUse"><stop class="k7ht9rb5w"/><stop offset="1" class="nr1zmhoko"/></linearGradient><linearGradient id="ipkqRnb" x1="7.653" x2="6.876" y1="14.326" y2="14.326" gradientUnits="userSpaceOnUse"><stop class="k7ht9rb5w"/><stop offset="1" class="nr1zmhoko"/></linearGradient><linearGradient id="i4jcFAe" x1="19.609" x2="18.8" y1="14.091" y2="14.091" gradientUnits="userSpaceOnUse"><stop class="k7ht9rb5w"/><stop offset=".843" class="nr1zmhoko"/></linearGradient><linearGradient id="i9ia15T" x1="20.098" x2="19.838" y1="12.954" y2="13.668" gradientUnits="userSpaceOnUse"><stop class="vdcy8-rqm"/><stop offset="1" class="s5qq57b7i"/></linearGradient><linearGradient id="io0TOxe" x1="22.66" x2="21.875" y1="14.076" y2="14.076" gradientUnits="userSpaceOnUse"><stop class="k7ht9rb5w"/><stop offset="1" class="nr1zmhoko"/></linearGradient><linearGradient id="iu6macd" x1="26.68" x2="25.895" y1="14.076" y2="14.076" gradientUnits="userSpaceOnUse"><stop class="k7ht9rb5w"/><stop offset="1" class="nr1zmhoko"/></linearGradient><linearGradient id="ibOofHd" x1="17.155" x2="17.155" y1="31.22" y2="14.683" gradientUnits="userSpaceOnUse"><stop class="rt2l-3btz"/><stop offset=".816" class="rt2l-3btz"/><stop offset=".84" class="xbdsddcti"/><stop offset="1" class="xbdsddcti"/></linearGradient><linearGradient id="ibBqwmd" x1="30.898" x2="25.424" y1="30.106" y2="30.106" gradientUnits="userSpaceOnUse"><stop class="ob-cu9big"/><stop offset="1" class="q3emu1bnv"/></linearGradient><linearGradient id="iecwobu" x1="1.325" x2="6.062" y1="27.076" y2="27.076" gradientUnits="userSpaceOnUse"><stop class="c-qt8mb_i"/><stop offset="1" class="bd585yhpn"/></linearGradient><linearGradient id="iPg8tBb" x1="16.005" x2="16.005" y1="14.898" y2="15.883" gradientUnits="userSpaceOnUse"><stop class="unozt67tp"/><stop offset="1" class="sjitiy62y"/></linearGradient><linearGradient id="ihK8Qkd" x1="5.702" x2="10.953" y1="26.595" y2="26.595" gradientUnits="userSpaceOnUse"><stop class="f9qxh5ill"/><stop offset="1" class="vtyalwber"/></linearGradient><linearGradient id="ivjITzd" x1="14.693" x2="19.942" y1="25.595" y2="25.595" gradientUnits="userSpaceOnUse"><stop class="f9qxh5ill"/><stop offset="1" class="vtyalwber"/></linearGradient><linearGradient id="i2DiICe" x1="23.703" x2="28.953" y1="26.6" y2="26.6" gradientUnits="userSpaceOnUse"><stop class="f9qxh5ill"/><stop offset="1" class="vtyalwber"/></linearGradient><linearGradient id="iQEffLc" x1="11.002" x2="21.012" y1="10.106" y2="10.106" gradientUnits="userSpaceOnUse"><stop class="ggu_wfbzm"/><stop offset="1" class="wkgwr0b5t"/></linearGradient><linearGradient id="iN0qaqd" x1="2" x2="30" y1="17.593" y2="17.593" gradientUnits="userSpaceOnUse"><stop class="v-gjwxkzy"/><stop offset=".281" class="ns_2pr4ua"/><stop offset=".698" class="iyq6ww7ks"/><stop offset="1" class="qnh43ssxq"/></linearGradient><linearGradient id="iixfplb" x1="8.208" x2="8.911" y1="6.164" y2="5.492" gradientUnits="userSpaceOnUse"><stop class="h7mqhibds"/><stop offset="1" class="j2ygk_bwh"/></linearGradient><linearGradient id="iVOcJyp" x1="9.995" x2="9.38" y1="4.211" y2="4.789" gradientUnits="userSpaceOnUse"><stop class="s72t5lbmv"/><stop offset="1" class="xin-zob4q"/></linearGradient><linearGradient id="iOsgFob" x1="25.357" x2="25.7" y1="8.977" y2="8.563" gradientUnits="userSpaceOnUse"><stop class="y08eo6evl"/><stop offset="1" class="e9x52g8_b"/></linearGradient><linearGradient id="iJjH6hs" x1="13.454" x2="13.454" y1="30.28" y2="22.005" gradientUnits="userSpaceOnUse"><stop class="jzougx6nx"/><stop offset="1" class="f46wt7b4x"/></linearGradient><linearGradient id="ieDCMxb" x1="4.624" x2="4.624" y1="30.106" y2="24.291" gradientUnits="userSpaceOnUse"><stop class="jzougx6nx"/><stop offset="1" class="f46wt7b4x"/></linearGradient><linearGradient id="imprwCe" x1="22.449" x2="22.449" y1="30.106" y2="24.291" gradientUnits="userSpaceOnUse"><stop class="jzougx6nx"/><stop offset="1" class="f46wt7b4x"/></linearGradient><filter id="iVc8XKd" width="6" height="7.52" x="3.995" y="23.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0784314 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="i5hNVnu" width="6" height="9.52" x="12.985" y="21.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0784314 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="iK9X3Ce" width="6" height="7.51" x="21.995" y="23.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0784314 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="iLWSWxz" width="10.81" height="6.8" x="10.605" y="6.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.376471 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.156863 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_5384" result="effect2_innerShadow_18_5384"/></filter><filter id="ijVX16b" width="3.255" height="2.247" x="2.995" y="10.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.141176 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="i1Zw7ye" width="3.255" height="2.247" x="6.975" y="10.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.141176 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="iuOtTBb" width="3.255" height="2.225" x="21.975" y="10.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.141176 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="i5QDr2d" width="3.255" height="2.245" x="25.995" y="10.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.141176 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="iLiPakV" width="1.28" height="1.28" x="11.845" y="7.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.352941 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.882353 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_5384" result="effect2_innerShadow_18_5384"/></filter><filter id="ieS68jc" width="1.28" height="1.28" x="14.855" y="7.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.6 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 1 0 0 0 0 0.595817 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_5384" result="effect2_innerShadow_18_5384"/></filter><filter id="iNHCU1z" width="1.13" height="1.13" x="18.855" y="11.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.32549 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="iQ8hdOS" width="2.28" height="2.28" x="11.845" y="9.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.352941 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.882353 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_5384" result="effect2_innerShadow_18_5384"/></filter><filter id="ilOKSwE" width="2.28" height="2.28" x="14.855" y="9.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.6 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 1 0 0 0 0 0.595817 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_5384" result="effect2_innerShadow_18_5384"/></filter><filter id="ihPN8Hb" width="2.13" height="1.13" x="17.855" y="8.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.32549 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="iiodeTc" width="2.28" height="2.28" x="3.985" y="7.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.196078 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="i2vsYPc" width="2.28" height="2.28" x="20.965" y="4.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.196078 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="isMCGgd" width="2.08" height="2.08" x="8.015" y="4.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.376471 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="iGZhIDc" width="2.273" height="2.28" x="24.952" y="7.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.584314 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5384"/></filter><filter id="iQwYtTb" width="2.806" height="9.246" x="12.755" y="21.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5384" stdDeviation=".3"/></filter><filter id="ioVHhcc" width="2.784" height="7.032" x="3.921" y="23.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5384" stdDeviation=".3"/></filter><filter id="ib5PLhb" width="2.784" height="7.032" x="21.745" y="23.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5384" stdDeviation=".3"/></filter><radialGradient id="iV7v0Sc" cx="0" cy="0" r="1" gradientTransform="rotate(124.985 -1.405 7.443)scale(.68602 .87215)" gradientUnits="userSpaceOnUse"><stop class="el6s99rcw"/><stop offset="1" class="o1sifhd9f"/></radialGradient><radialGradient id="imEVkQe" cx="0" cy="0" r="1" gradientTransform="rotate(124.985 .585 8.48)scale(.68602 .87215)" gradientUnits="userSpaceOnUse"><stop class="el6s99rcw"/><stop offset="1" class="o1sifhd9f"/></radialGradient><radialGradient id="iy5fX4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.39727 .64235 -.77769 -.48097 22.876 12.402)" gradientUnits="userSpaceOnUse"><stop class="el6s99rcw"/><stop offset="1" class="o1sifhd9f"/></radialGradient><radialGradient id="ifTtKsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.39727 .64235 -.77769 -.48097 26.897 12.403)" gradientUnits="userSpaceOnUse"><stop class="el6s99rcw"/><stop offset="1" class="o1sifhd9f"/></radialGradient><radialGradient id="i77AHOc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.54124 0 0 -1.77242 5.536 12.108)" gradientUnits="userSpaceOnUse"><stop class="t8dn61bqb"/><stop offset="1" class="oz8qgi5yb"/></radialGradient><radialGradient id="ijJ1kae" cx="0" cy="0" r="1" gradientTransform="matrix(-2.54126 0 0 -1.77242 9.516 12.108)" gradientUnits="userSpaceOnUse"><stop class="t8dn61bqb"/><stop offset="1" class="oz8qgi5yb"/></radialGradient><radialGradient id="iowHfVg" cx="0" cy="0" r="1" gradientTransform="matrix(-2.54126 0 0 -1.75307 24.516 12.118)" gradientUnits="userSpaceOnUse"><stop class="t8dn61bqb"/><stop offset="1" class="oz8qgi5yb"/></radialGradient><radialGradient id="iLPrbqQ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.54124 0 0 -1.77076 28.536 12.12)" gradientUnits="userSpaceOnUse"><stop class="t8dn61bqb"/><stop offset="1" class="oz8qgi5yb"/></radialGradient><radialGradient id="iU1sTdb" cx="0" cy="0" r="1" gradientTransform="matrix(.38577 -.42956 1.02063 .9166 19.005 12.322)" gradientUnits="userSpaceOnUse"><stop class="vg3e3xblh"/><stop offset="1" class="v4ab-469b"/></radialGradient><radialGradient id="ihoYoTd" cx="0" cy="0" r="1" gradientTransform="matrix(.77942 -.42955 .86787 1.57474 18.005 9.312)" gradientUnits="userSpaceOnUse"><stop class="vg3e3xblh"/><stop offset="1" class="v4ab-469b"/></radialGradient><radialGradient id="iE3EIGA" cx="0" cy="0" r="1" gradientTransform="rotate(140.057 2.045 3.27)scale(.8423)" gradientUnits="userSpaceOnUse"><stop class="beozv040a"/><stop offset=".938" class="z--md5bru"/></radialGradient><radialGradient id="ioRtTuc" cx="0" cy="0" r="1" gradientTransform="rotate(140.364 2.34 5.626)scale(.68725)" gradientUnits="userSpaceOnUse"><stop class="w0ue4x4aa"/><stop offset="1" class="ofb4uwbqg"/></radialGradient><radialGradient id="iWaNZEd" cx="0" cy="0" r="1" gradientTransform="rotate(140.364 4.871 4.843)scale(.68725)" gradientUnits="userSpaceOnUse"><stop class="gzbolmbsn"/><stop offset="1" class="dfe-jxbok"/></radialGradient><radialGradient id="ix9jfxc" cx="0" cy="0" r="1" gradientTransform="rotate(141.889 10.231 8.831)scale(.82073)" gradientUnits="userSpaceOnUse"><stop class="x3x37iffo"/><stop offset=".354" class="a1x712bat"/><stop offset=".891" class="wf6w1g1ak"/></radialGradient><radialGradient id="i6AeWpd" cx="0" cy="0" r="1" gradientTransform="rotate(141.889 12.725 9.681)scale(.82073)" gradientUnits="userSpaceOnUse"><stop class="x3x37iffo"/><stop offset=".354" class="a1x712bat"/><stop offset=".891" class="wf6w1g1ak"/></radialGradient><radialGradient id="i8d8vKe" cx="0" cy="0" r="1" gradientTransform="rotate(140.057 13.028 7.267)scale(.8423)" gradientUnits="userSpaceOnUse"><stop class="beozv040a"/><stop offset=".938" class="z--md5bru"/></radialGradient><radialGradient id="in7BF2G" cx="0" cy="0" r="1" gradientTransform="matrix(-.74505 .62256 -.67049 -.8024 27.068 7.086)" gradientUnits="userSpaceOnUse"><stop class="rmjen1jyz"/><stop offset="1" class="oo5vh5bln"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:stadium" /></template>
<style>
.a1x712bat {
  stop-color: var(--svg-color--ffcb53, #FFCB53);
}

.a8h6vacfd {
  d: path("M22.985 12.076h-1.01v4h1.01z");
}

.bd585yhpn {
  stop-color: var(--svg-color--6f6774, #6F6774);
  stop-opacity: 0;
}

.beozv040a {
  stop-color: var(--svg-color--ff5560, #FF5560);
}

.bow9bs5yu {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M25.095 8.916c.2.2.52.2.72 0l.96-.96c.2-.2.2-.52 0-.72s-.52-.2-.72 0l-.96.96c-.19.2-.19.52 0 .72");
}

.c-qt8mb_i {
  stop-color: var(--svg-color--6f6774, #6F6774);
}

.c725cyvoy {
  fill: var(--svg-color--42dc80, #42DC80);
  d: path("M16.565 12.096h-1.14c-.23 0-.42-.19-.42-.42v-1.14c0-.23.19-.42.42-.42h1.14c.23 0 .42.19.42.42v1.14a.41.41 0 0 1-.42.42");
}

.cacou6b3s {
  d: path("M19.995 13.076h-1.01v2.03h1.01z");
}

.cowxu0sqh {
  d: path("M8.165 5.916c.2.2.52.2.72 0l.96-.96c.2-.2.2-.52 0-.72s-.52-.2-.72 0l-.96.96c-.2.2-.2.52 0 .72");
}

.damd2ry4j {
  d: path("M19.495 9.096h-1a.49.49 0 0 1 0-.98h1a.49.49 0 0 1 0 .98");
}

.dfe-jxbok {
  stop-color: var(--svg-color--422f51, #422F51);
}

.dncv_tyrt {
  fill: var(--svg-color--ff8738, #FF8738);
  d: path("M19.495 9.096h-1a.49.49 0 0 1 0-.98h1a.49.49 0 0 1 0 .98");
}

.e9x52g8_b {
  stop-color: var(--svg-color--3e956f, #3E956F);
  stop-opacity: 0;
}

.efz0mebro {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M5.805 24.46c-.328.038-.984.374-.984 1.415v3.818");
}

.el6s99rcw {
  stop-color: var(--svg-color--c1b3bc, #C1B3BC);
}

.f46wt7b4x {
  stop-color: var(--svg-color--624f74, #624F74);
  stop-opacity: 0;
}

.f9qxh5ill {
  stop-color: var(--svg-color--4e3e5c, #4E3E5C);
}

.fjvcgupkr {
  d: path("M6.975 11.516v1.14c0 .32.4.53.77.41l1.95-.62c.38-.12.38-.55 0-.67l-2.01-.65c-.34-.09-.71.1-.71.39");
}

.ft5dv1b6b {
  fill: none;
}

.g-ff56f6c {
  d: path("M25.995 11.526v1.14c0 .32.4.53.77.41l1.95-.61c.38-.12.38-.54 0-.67l-2.01-.65c-.34-.11-.71.09-.71.38");
}

.ggu_wfbzm {
  stop-color: var(--svg-color--3c373f, #3C373F);
}

.gxr7nacaj {
  d: path("M7.975 12.576h-1v3.5h1z");
}

.gxsqe_b3r {
  fill: var(--svg-color--42dc80, #42DC80);
  d: path("M15.495 9.096a.49.49 0 1 1 .49-.49c.01.27-.21.49-.49.49");
}

.gzbolmbsn {
  stop-color: var(--svg-color--8b6fa2, #8B6FA2);
}

.h7mqhibds {
  stop-color: var(--svg-color--ba652c, #BA652C);
}

.hwn2b0b0z {
  d: path("M7.495 9.106a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.ibvsa_2cr {
  fill: var(--svg-color--fab240, #FAB240);
  d: path("M8.165 5.916c.2.2.52.2.72 0l.96-.96c.2-.2.2-.52 0-.72s-.52-.2-.72 0l-.96.96c-.2.2-.2.52 0 .72");
}

.int5dybyp {
  d: path("M11.475 6.106a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.iyq6ww7ks {
  stop-color: var(--svg-color--ef3849, #EF3849);
}

.j2ygk_bwh {
  stop-color: var(--svg-color--ba652c, #BA652C);
  stop-opacity: 0;
}

.ja-liqbdz {
  d: path("M27.005 12.076h-1.01v4h1.01z");
}

.japjmjpsm {
  fill: var(--svg-color--836898, #836898);
  d: path("M22.795 6.956c-.2.2-.52.2-.72 0l-.96-.96c-.2-.2-.2-.52 0-.72s.52-.2.72 0l.96.96c.2.2.2.52 0 .72");
}

.jzougx6nx {
  stop-color: var(--svg-color--624f74, #624F74);
}

.k7ht9rb5w {
  stop-color: var(--svg-color--e1d8e1, #E1D8E1);
}

.kpdjb8zuf {
  d: path("M27.445 5.116a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.l4n1dqaem {
  d: path("M30.005 18.036v12.07h-28v-12.07c0-.1.01-.2.02-.3c.02-.22.06-.43.13-.63c.01-.02.01-.04.02-.06a2.95 2.95 0 0 1 2.76-1.94h22.14c1.27 0 2.35.81 2.76 1.94c.01.02.01.04.02.06c.05.15.09.32.11.49c.03.14.04.29.04.44");
}

.lxpy9kb1h {
  d: path("M23.495 10.106a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.mno310bpx {
  d: path("M25.095 8.916c.2.2.52.2.72 0l.96-.96c.2-.2.2-.52 0-.72s-.52-.2-.72 0l-.96.96c-.19.2-.19.52 0 .72");
}

.n8ozs5pyu {
  fill: var(--svg-color--48dc86, #48DC86);
  d: path("M25.095 8.916c.2.2.52.2.72 0l.96-.96c.2-.2.2-.52 0-.72s-.52-.2-.72 0l-.96.96c-.19.2-.19.52 0 .72");
}

.nclx1-4lb {
  fill: var(--svg-color--ffb340, #FFB340);
  d: path("M13.555 12.096h-1.14c-.23 0-.42-.19-.42-.42v-1.14c0-.23.19-.42.42-.42h1.14c.23 0 .42.19.42.42v1.14a.41.41 0 0 1-.42.42");
}

.ni0d10bhc {
  d: path("M19.495 12.106a.49.49 0 1 1 .002-.982a.49.49 0 0 1-.002.982");
}

.nq0adpaug {
  d: path("M3.995 12.576h-1v3.5h1z");
}

.nr1zmhoko {
  stop-color: var(--svg-color--79767b, #79767B);
}

.ns_2pr4ua {
  stop-color: var(--svg-color--e03970, #E03970);
}

.o1sifhd9f {
  stop-color: var(--svg-color--c1b3bc, #C1B3BC);
  stop-opacity: 0;
}

.ob-cu9big {
  stop-color: var(--svg-color--f7f5f8, #F7F5F8);
}

.ofb4uwbqg {
  stop-color: var(--svg-color--358a65, #358A65);
}

.oo5vh5bln {
  stop-color: var(--svg-color--55ff91, #55FF91);
  stop-opacity: 0;
}

.oz8qgi5yb {
  stop-color: var(--svg-color--bb2263, #BB2263);
}

.p2om2ur3c {
  fill: var(--svg-color--ff8738, #FF8738);
  d: path("M19.495 12.106a.49.49 0 1 1 .002-.982a.49.49 0 0 1-.002.982");
}

.p8oyfrbqf {
  d: path("M2.995 11.516v1.14c0 .32.4.53.77.41l1.95-.62c.38-.12.38-.55 0-.67l-2.01-.65c-.34-.09-.71.1-.71.39");
}

.q3emu1bnv {
  stop-color: var(--svg-color--f7f5f8, #F7F5F8);
  stop-opacity: 0;
}

.qnh43ssxq {
  stop-color: var(--svg-color--ff525e, #FF525E);
}

.rmjen1jyz {
  stop-color: var(--svg-color--55ff91, #55FF91);
}

.rt2l-3btz {
  stop-color: var(--svg-color--d5c6de, #D5C6DE);
}

.s5qq57b7i {
  stop-color: var(--svg-color--7d7282, #7D7282);
  stop-opacity: 0;
}

.s60dpoulj {
  d: path("M28.475 10.086a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.s72t5lbmv {
  stop-color: var(--svg-color--fff05c, #FFF05C);
}

.sdqjcrdtt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M23.629 24.46c-.328.038-.984.374-.984 1.415v3.818");
}

.sjitiy62y {
  stop-color: var(--svg-color--b4b3b5, #B4B3B5);
  stop-opacity: 0;
}

.t3rsy_bwp {
  d: path("M6.995 23.086c-1.66 0-3 1.34-3 3v4.02h6v-4.02c0-1.65-1.35-3-3-3");
}

.t8dn61bqb {
  stop-color: var(--svg-color--ff4755, #FF4755);
}

.unozt67tp {
  stop-color: var(--svg-color--b4b3b5, #B4B3B5);
}

.upxj7db1i {
  d: path("M15.985 21.086c-1.66 0-3 1.34-3 3v6.02h6v-6.02c0-1.66-1.34-3-3-3");
}

.us5o8sbqa {
  fill: var(--svg-color--ffb340, #FFB340);
  d: path("M12.485 9.096a.49.49 0 1 1 .49-.49c.01.27-.22.49-.49.49");
}

.utckpdtss {
  d: path("M5.475 5.106a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.v-gjwxkzy {
  stop-color: var(--svg-color--8d3255, #8D3255);
}

.v4ab-469b {
  stop-color: var(--svg-color--ffc137, #FFC137);
  stop-opacity: 0;
}

.vdcy8-rqm {
  stop-color: var(--svg-color--7d7282, #7D7282);
}

.vg3e3xblh {
  stop-color: var(--svg-color--ffc137, #FFC137);
}

.vtyalwber {
  stop-color: var(--svg-color--1e1a21, #1E1A21);
}

.w0ue4x4aa {
  stop-color: var(--svg-color--53f48b, #53F48B);
}

.waw1jabny {
  d: path("M21.975 11.526v1.13c0 .31.4.53.77.41l1.95-.61c.38-.12.38-.54 0-.66l-2.01-.64c-.34-.11-.71.08-.71.37");
}

.wcv_bnbjh {
  d: path("M20.055 13.106h-8.09a.96.96 0 0 1-.96-.96v-4.08c0-.53.43-.96.96-.96h8.09c.53 0 .96.43.96.96v4.08c0 .53-.43.96-.96.96");
}

.wf6w1g1ak {
  stop-color: var(--svg-color--a87a39, #A87A39);
}

.wkgwr0b5t {
  stop-color: var(--svg-color--574468, #574468);
}

.x2wudq_vz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M14.661 22.247c-.335.053-1.006.531-1.006 2.012v5.434");
}

.x3x37iffo {
  stop-color: var(--svg-color--fede95, #FEDE95);
}

.x6yiklbhx {
  d: path("M12.995 13.106h-.99v2.04h.99z");
}

.xbdsddcti {
  stop-color: var(--svg-color--d2cfd4, #D2CFD4);
}

.xeo7t_l0i {
  fill: var(--svg-color--836898, #836898);
  d: path("M5.815 9.916c-.2.2-.52.2-.72 0l-.96-.96c-.2-.2-.2-.52 0-.72s.52-.2.72 0l.96.96c.2.2.2.52 0 .72");
}

.xin-zob4q {
  stop-color: var(--svg-color--fff05c, #FFF05C);
  stop-opacity: 0;
}

.y08eo6evl {
  stop-color: var(--svg-color--3e956f, #3E956F);
}

.z--md5bru {
  stop-color: var(--svg-color--8b2b57, #8B2B57);
}

.zhfi9sqka {
  d: path("M30.005 18.026v.07h-28v-.07c0-.1.01-.2.02-.3c.02-.22.06-.43.13-.63h27.7c.05.15.09.32.11.49c.03.14.04.29.04.44");
}

.zr2rkmfgv {
  d: path("M24.995 23.096c-1.66 0-3 1.34-3 3v4.01h6v-4.01c0-1.65-1.35-3-3-3");
}

</style>
