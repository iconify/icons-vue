<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iikVaVd)"><path fill="url(#iLPiRmI)" clip-rule="evenodd" class="ai35b8b-u"/><path fill="url(#iBjbGOc)" clip-rule="evenodd" class="ai35b8b-u"/><path fill="url(#iWWkq5d)" clip-rule="evenodd" class="ai35b8b-u"/><path fill="url(#iWgt3XR)" clip-rule="evenodd" class="ai35b8b-u"/><path fill="url(#iCTWcne)" clip-rule="evenodd" class="ai35b8b-u"/><path fill="url(#iu4wqle)" clip-rule="evenodd" class="ai35b8b-u"/><path fill="url(#irYxnYd)" clip-rule="evenodd" class="ai35b8b-u"/><path fill="url(#i5z94kc)" clip-rule="evenodd" class="ai35b8b-u"/><path fill="url(#iLOGCND)" clip-rule="evenodd" class="ai35b8b-u"/><path fill="url(#ipTLmNd)" clip-rule="evenodd" class="ai35b8b-u"/></g><path fill="url(#iXYk6Zd)" clip-rule="evenodd" class="ai35b8b-u"/><path fill="url(#iwyfQTb)" class="g8ltv_b3r"/><path fill="url(#its2bOc)" class="g8ltv_b3r"/><path fill="url(#iYYRTGb)" class="g8ltv_b3r"/><path fill="url(#iMVthge)" class="g8ltv_b3r"/><path fill="url(#i6DOAAb)" class="nmtuk6b6c"/><g filter="url(#i6OnIrb)"><path fill="url(#iuH63Nc)" class="vrfgrpb3q"/></g><g filter="url(#iSfcpxe)"><path fill="url(#i9kGu6b)" class="vrfgrpb3q"/></g><g filter="url(#idAQPrc)"><path fill="url(#io4CjHc)" class="e63vclc3q"/><path fill="url(#iNT3Std)" class="e63vclc3q"/></g><g filter="url(#iv37z2d)"><path class="lccpi7ueh"/><path fill="url(#i6pY7Me)" class="dxjrdrbpa"/></g><g filter="url(#ipBfWOO)"><path class="t6jqthc7h"/><path fill="url(#ivXhqye)" class="pp7rrkbql"/></g><g filter="url(#isG1pAe)"><path fill="url(#il98rHd)" class="l28oc64ml"/><path fill="url(#iAbGLjb)" class="l28oc64ml"/><path fill="url(#i3EBN7d)" class="l28oc64ml"/><path fill="url(#iWDvjcc)" class="l28oc64ml"/><path fill="url(#iebU2xe)" class="l28oc64ml"/><path fill="url(#ii4Jcce)" class="l28oc64ml"/><path fill="url(#ixGhFZb)" class="l28oc64ml"/></g><path fill="url(#iOrasIb)" class="l28oc64ml"/><g filter="url(#iA65ywd)"><path class="f6jngu_1i"/></g><g filter="url(#iLzTIJd)"><path class="hbq5-kbdc"/><path fill="url(#itM3Obb)" class="wycv0qbje"/><path fill="url(#iijPX1c)" class="wycv0qbje"/><path fill="url(#ivurZcP)" class="wycv0qbje"/></g><path fill="url(#iJsBIXd)" class="wycv0qbje"/><path fill="url(#iyhkRNd)" class="wycv0qbje"/><g filter="url(#i0C6oVF)"><path class="rl0j2vb6c"/></g><g filter="url(#iG3VWjd)"><path class="k6prsrbvr"/></g><path class="e1_0dwykl"/><path fill="url(#isZm2Sc)" class="e8i_2obba"/><path class="x37z32b5t"/><g filter="url(#i78Eypv)"><path class="fkq5jlesp"/><path fill="url(#i2Ziphc)" class="j9w0c_7np"/></g><g filter="url(#ietY8fd)"><path fill="url(#iebqjbU)" class="s91tejbjx"/></g><path class="up50vjm_w"/><path fill="url(#i5G8OEy)" class="wq2ua4b3u"/><path class="lrxv66bwv"/><g filter="url(#i6sSjcE)"><path fill="url(#ijEt05b)" class="aarp0pexo"/></g><g filter="url(#i7uqrLe)"><ellipse transform="rotate(-27.914 12.422 12.691)" class="xl55yte0p"/><ellipse fill="url(#iNAxhxd)" transform="rotate(-27.914 12.422 12.691)" class="nr1w56t5z"/></g><g filter="url(#iORvXNb)"><path fill="url(#ij2PGKe)" class="ue2icdbry"/><path fill="url(#inTDKLc)" class="ue2icdbry"/></g><g filter="url(#iOOv7rc)"><path fill="url(#iX24QRL)" class="ged_79eih"/><path fill="url(#i0LMcMb)" class="ged_79eih"/><path fill="url(#iIxClXd)" class="ged_79eih"/></g><g filter="url(#iKJZRPe)"><path stroke="url(#icWtJyb)" class="q06k5hbty"/></g><g filter="url(#ibDhN1d)"><path clip-rule="evenodd" class="io_ia3bpt"/></g><g filter="url(#il34qSd)"><path class="kucyrydzb"/></g><g filter="url(#ioZQcsP)"><path clip-rule="evenodd" class="nwtv201rg"/></g><g filter="url(#iAQ1POe)"><path class="tc99wkbfq"/></g><g filter="url(#igCClQQ)"><path stroke="url(#iGy5EMj)" clip-rule="evenodd" class="dwm3sbcbq"/><path stroke="url(#ijx4nbc)" clip-rule="evenodd" class="dwm3sbcbq"/></g><path clip-rule="evenodd" class="v-qwllbxk"/><defs><radialGradient id="iBjbGOc" cx="0" cy="0" r="1" gradientTransform="matrix(2.35458 -4.89027 11.15016 5.3686 22.075 21.488)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iWWkq5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.18112 7.47124 -6.99358 -.16954 14.83 16.009)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iWgt3XR" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 2.787 10.658)scale(5.38912 6.63371)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iCTWcne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38115 1.9697 -1.79037 -1.2554 9.193 13.926)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iu4wqle" cx="0" cy="0" r="1" gradientTransform="matrix(-3.14698 -.70182 1.03168 -4.62609 9.918 11.91)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="irYxnYd" cx="0" cy="0" r="1" gradientTransform="matrix(2.92069 4.27899 -7.46741 5.097 10.552 3.398)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="i5z94kc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49424 1.6301 -2.27804 -2.08817 23.162 5.866)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iLOGCND" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 12.05 8.082)scale(2.59355 5.64322)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="ipTLmNd" cx="0" cy="0" r="1" gradientTransform="rotate(156.949 11.103 10.72)scale(4.62569 7.37013)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iwyfQTb" cx="0" cy="0" r="1" gradientTransform="rotate(167.548 9.342 14.18)scale(15.0733 14.5482)" gradientUnits="userSpaceOnUse"><stop class="hkyavpram"/><stop offset=".627" class="s2s91xb1y"/><stop offset="1" class="k55h_abwi"/></radialGradient><radialGradient id="iYYRTGb" cx="0" cy="0" r="1" gradientTransform="matrix(-13.622 0 0 -10.1312 19.443 29.315)" gradientUnits="userSpaceOnUse"><stop offset=".855" class="qz1bsbh9m"/><stop offset="1" class="uea4-671p"/></radialGradient><radialGradient id="iMVthge" cx="0" cy="0" r="1" gradientTransform="matrix(-6.06249 1.4688 -.83299 -3.43817 13.273 19.889)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="cl47hw9gv"/><stop offset="1" class="j-vbdhkdl"/></radialGradient><radialGradient id="i6DOAAb" cx="0" cy="0" r="1" gradientTransform="matrix(3.43666 3.13974 -4.13338 4.52426 14.226 20.951)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="cjdb4jgex"/><stop offset=".866" class="ge-n2dbmh"/></radialGradient><radialGradient id="io4CjHc" cx="0" cy="0" r="1" gradientTransform="matrix(3.36206 -1.52821 1.86588 4.10492 21.193 14.22)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iNT3Std" cx="0" cy="0" r="1" gradientTransform="matrix(1.34709 .38488 -.20235 .70822 22.573 11.22)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="i6pY7Me" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 49.93 -54.308)scale(1.76215)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="ivXhqye" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64366 0 0 -1.57226 9.433 13.627)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="il98rHd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.78464 4.05089 -5.42204 -11.75807 19.598 12.901)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iAbGLjb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8497 1.5073 -1.27885 -2.41777 18.303 13.843)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="i3EBN7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.13047 -5.46391 6.9327 1.43435 12.792 22.062)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iWDvjcc" cx="0" cy="0" r="1" gradientTransform="matrix(.82624 10.93754 -13.14545 .99303 15.736 12.375)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="pj__wrb2a"/><stop offset="1" class="hiw8w_whp"/></radialGradient><radialGradient id="iebU2xe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.74293 1.04138 -1.79294 -13.33097 16.597 16.054)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="ii4Jcce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.55439 2.23461 0 18.845 12.336)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="ixGhFZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.83701 2.10533 0 13.145 12.454)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iOrasIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.81938 0 0 -5.98945 22.619 14.345)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="itM3Obb" cx="0" cy="0" r="1" gradientTransform="matrix(-.94208 -3.30895 1.89343 -.53907 16.796 15.327)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iyhkRNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73102 1.23645 -1.65614 -2.31857 16.125 14.844)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="isZm2Sc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09588 -1.74311 0 18.684 12.82)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="cqpaw5wjj"/></radialGradient><radialGradient id="i2Ziphc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.355 1.967)scale(.51097 .70347)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5G8OEy" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09588 -1.74312 0 12.789 12.82)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="cqpaw5wjj"/></radialGradient><radialGradient id="iNAxhxd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.657 .454)scale(.66743 .80227)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ij2PGKe" cx="0" cy="0" r="1" gradientTransform="rotate(48.799 -1.963 10.732)scale(4.20689 8.73116)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="inTDKLc" cx="0" cy="0" r="1" gradientTransform="rotate(132.562 4.835 5.355)scale(3.97513 3.22765)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iX24QRL" cx="0" cy="0" r="1" gradientTransform="rotate(116.153 8.202 7.242)scale(6.47194 9.32215)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="i0LMcMb" cx="0" cy="0" r="1" gradientTransform="rotate(105.258 7.664 9.515)scale(4.39774 7.99281)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iIxClXd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.73188 -8.33707 7.54427 -4.28191 17.48 11.853)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="iGy5EMj" cx="0" cy="0" r="1" gradientTransform="rotate(-74.859 19.989 -1.558)scale(.68794 1.67216)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="s3m8e5eat"/><stop offset=".581" class="ugfjl15nl"/></radialGradient><radialGradient id="ijx4nbc" cx="0" cy="0" r="1" gradientTransform="matrix(.53516 -.58203 .42042 .38656 14.182 18.37)" gradientUnits="userSpaceOnUse"><stop offset=".065" class="s3m8e5eat"/><stop offset=".571" class="ugfjl15nl"/></radialGradient><filter id="iikVaVd" width="20.535" height="21.036" x="5.594" y="1.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21895"/></filter><filter id="i6OnIrb" width="4.497" height="4.347" x="7.234" y="11.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21895"/></filter><filter id="iSfcpxe" width="4.497" height="4.597" x="7.234" y="11.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21895"/></filter><filter id="idAQPrc" width="4.347" height="4.597" x="20.083" y="11.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21895"/></filter><filter id="iv37z2d" width="3.902" height="3.902" x="20.306" y="11.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".25"/></filter><filter id="ipBfWOO" width="3.702" height="3.702" x="7.582" y="11.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".2"/></filter><filter id="isG1pAe" width="13.765" height="15.092" x="8.854" y="6.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21895"/></filter><filter id="iA65ywd" width="3.536" height="4.622" x="13.749" y="12.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".25"/></filter><filter id="iLzTIJd" width="3.036" height="4.122" x="14.218" y="12.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".125"/></filter><filter id="i0C6oVF" width="3.984" height="1.736" x="17.079" y="11.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21895"/></filter><filter id="iG3VWjd" width="3.984" height="1.736" x="10.41" y="11.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21895"/></filter><filter id="i78Eypv" width=".993" height=".87" x="17.727" y="12.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".05"/></filter><filter id="ietY8fd" width="1.064" height="1.093" x="18.897" y="12.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".1"/></filter><filter id="i6sSjcE" width="1.192" height="1.265" x="12.896" y="12.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".1"/></filter><filter id="i7uqrLe" width="1.163" height=".881" x="11.841" y="12.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".05"/></filter><filter id="iORvXNb" width="6.208" height="6.516" x="6.939" y="4.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".375"/></filter><filter id="iOOv7rc" width="12.865" height="8.485" x="10.843" y="2.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".375"/></filter><filter id="iKJZRPe" width="1.336" height="2.909" x="11.531" y="4.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".1"/></filter><filter id="ibDhN1d" width="3.18" height="1.857" x="10.746" y="9.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21895"/></filter><filter id="il34qSd" width="2.83" height="1.507" x="10.821" y="9.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".1"/></filter><filter id="ioZQcsP" width="3.18" height="1.857" x="17.746" y="9.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21895"/></filter><filter id="iAQ1POe" width="2.83" height="1.507" x="17.821" y="9.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".1"/></filter><filter id="igCClQQ" width="3.791" height="1.495" x="13.841" y="17.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21895" stdDeviation=".1"/></filter><linearGradient id="iLPiRmI" x1="22.076" x2="12.884" y1="4.236" y2="21.261" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iXYk6Zd" x1="15.736" x2="15.736" y1="22.891" y2="20.99" gradientUnits="userSpaceOnUse"><stop class="hqpka7yim"/><stop offset="1" class="jj4p15bbx"/></linearGradient><linearGradient id="its2bOc" x1="15.736" x2="15.736" y1="30.295" y2="29.451" gradientUnits="userSpaceOnUse"><stop class="kba1trwhz"/><stop offset="1" class="pb6-h6b6v"/></linearGradient><linearGradient id="iuH63Nc" x1="7.234" x2="9.743" y1="13.745" y2="13.745" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="i9kGu6b" x1="7.234" x2="11.231" y1="13.745" y2="13.745" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iijPX1c" x1="14.323" x2="15.477" y1="15.35" y2="15.492" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="ivurZcP" x1="15.736" x2="15.736" y1="16.504" y2="15.68" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iJsBIXd" x1="15.842" x2="15.842" y1="16.469" y2="16.281" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="iebqjbU" x1="19.734" x2="19.311" y1="12.893" y2="13.154" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijEt05b" x1="13.793" x2="13.37" y1="12.893" y2="13.154" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icWtJyb" x1="11.831" x2="12.567" y1="5.255" y2="6.975" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-frowning-medium-light" /></template>
<style>
.aarp0pexo {
  d: path("M13.887 13.24c0-.39-.316-.65-.402-.728l-.39.377l.24.488z");
}

.ai35b8b-u {
  fill-rule: evenodd;
  d: path("M25.442 15.531a4.4 4.4 0 0 0 .437-1.927a4.4 4.4 0 0 0-.363-1.764h.008a4.3 4.3 0 0 0-.38-.693l-.003-.004a4.4 4.4 0 0 1-.71-2.392v-.014a4.457 4.457 0 0 0-4.457-4.456a.73.73 0 0 1-.615-.314a4.47 4.47 0 0 0-3.623-1.86c-1.49 0-2.816.739-3.622 1.86a.76.76 0 0 1-.615.314q-.058 0-.115.002a4.457 4.457 0 0 0-4.342 4.454v.014a4.4 4.4 0 0 1-.71 2.392l-.004.005a4.46 4.46 0 0 0-.734 2.456c0 .697.164 1.34.437 1.927a.7.7 0 0 1 0 .615a4.4 4.4 0 0 0-.437 1.9a4.34 4.34 0 0 0 4.346 4.347h11.592a4.34 4.34 0 0 0 4.347-4.347c0-.683-.164-1.326-.437-1.9a.7.7 0 0 1 0-.615m-16.56-3.61h-.017l1.619 3.182c.166 3.786 1.644 0 5.252 0s5.182 4.214 5.349.428l1.534-4.318c-.073-1.682-1.291-1.8-1.534-1.8h-4.35a5.22 5.22 0 0 1-4.308-2.26a.356.356 0 0 0-.623.069l-.11.262a3.1 3.1 0 0 1-1.608 1.667l-.069.028q-.037.016-.069.027c-.319.166-1.067.662-1.094 1.944l.014.413z");
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

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.cjdb4jgex {
  stop-color: var(--svg-color--b77771, #B77771);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl47hw9gv {
  stop-color: var(--svg-color--603570, #603570);
}

.cqpaw5wjj {
  stop-color: var(--svg-color--664b41, #664B41);
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dwm3sbcbq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.918 18.267c-.958-.557-1.98-.231-2.36-.002a.275.275 0 1 1-.284-.471c.484-.291 1.729-.695 2.92-.002a.275.275 0 0 1-.276.475Z");
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.dxjrdrbpa {
  d: path("M22.257 15.078a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.e1_0dwykl {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.966 11.81c.882 0 1.627.607 1.83 1.43a.37.37 0 0 1-.362.46h-3.013a.31.31 0 0 1-.307-.368a1.89 1.89 0 0 1 1.852-1.523");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.e63vclc3q {
  d: path("M22.257 15.8a2.173 2.173 0 1 0 0-4.346a2.173 2.173 0 0 0 0 4.346");
}

.e8i_2obba {
  d: path("M18.686 12.176a1.206 1.206 0 0 1 1.162 1.523h-2.329a1.2 1.2 0 0 1-.043-.317a1.21 1.21 0 0 1 1.21-1.206");
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.f6jngu_1i {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.206 13.326l-.923 2.296a.728.728 0 0 0 .703.945h1.062a.73.73 0 0 0 .703-.945l-.718-2.296c-.153-.508-.666-.508-.827 0");
}

.fkq5jlesp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.598 12.431c.086.115-.094.255-.298.408s-.356.26-.442.145c-.085-.115.01-.332.215-.485c.204-.152.439-.183.525-.068");
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.g8ltv_b3r {
  d: path("M25.651 29.967v-.387c0-5.346-4.436-9.691-9.915-9.691s-9.915 4.335-9.915 9.691v.387z");
}

.ge-n2dbmh {
  stop-color: var(--svg-color--efb89d, #EFB89D);
}

.ged_79eih {
  d: path("M15.35 3.23c-1.969-.234-3.297 1.25-3.757 1.73c2.083 4.89 5.282 4.425 8.83 4.03c2.124-.236 2.355.732 2.536 1.2c-.589-5.479-4.064-6.538-7.61-6.96");
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.hbq5-kbdc {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.22 13.14l-.718 2.295a.728.728 0 0 0 .703.945h1.062a.73.73 0 0 0 .704-.945l-.718-2.296c-.154-.509-.872-.509-1.033 0");
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

.hiw8w_whp {
  stop-color: var(--svg-color--b36d8d, #B36D8D);
}

.hkyavpram {
  stop-color: var(--svg-color--9b7fd9, #9B7FD9);
}

.hqpka7yim {
  stop-color: var(--svg-color--d08d9c, #D08D9C);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.io_ia3bpt {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("M13.598 9.825a.375.375 0 0 1 .036.529c-.37.426-.864.685-1.318.836a3.8 3.8 0 0 1-1.202.199a.375.375 0 1 1 .015-.75a3 3 0 0 0 .95-.16c.374-.125.735-.325.99-.617a.375.375 0 0 1 .529-.037");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j-vbdhkdl {
  stop-color: var(--svg-color--603570, #603570);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.j9w0c_7np {
  d: path("M18.598 12.431c.086.115-.094.255-.298.408s-.356.26-.442.145c-.085-.115.01-.332.215-.485c.204-.152.439-.183.525-.068");
}

.jj4p15bbx {
  stop-color: var(--svg-color--d08d9c, #D08D9C);
  stop-opacity: 0;
}

.k55h_abwi {
  stop-color: var(--svg-color--6b509d, #6B509D);
}

.k6prsrbvr {
  fill: var(--svg-color--35292e, #35292E);
  d: path("M14.194 12.858c-.359-.63-.904-1.128-2.077-1.128c-.513 0-1.009.142-1.449.498c-.363.293-.314.669-.033.81l.751.428c.88-.285 1.854-.323 2.808-.608");
}

.kba1trwhz {
  stop-color: var(--svg-color--7052bb, #7052BB);
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kucyrydzb {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.121 11.014c.52.01 1.606-.188 2.23-.906");
}

.l28oc64ml {
  d: path("M8.865 11.922h.016l-.014-.359l-.013-.413c.027-1.282.775-1.778 1.094-1.944q.031-.01.07-.027l.068-.028a3.1 3.1 0 0 0 1.607-1.667l.111-.262a.356.356 0 0 1 .623-.069a5.22 5.22 0 0 0 4.308 2.26h4.35c.243 0 1.461.118 1.534 1.8l-.16 4.15c-.167 3.786-3.123 6.328-6.732 6.328s-6.564-2.542-6.73-6.327z");
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lccpi7ueh {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M22.257 15.078a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lrxv66bwv {
  fill: var(--svg-color--000, #000);
  d: path("M13.477 13.382a.69.69 0 0 0-.69-.69a.688.688 0 0 0-.615 1.007h1.222a.7.7 0 0 0 .082-.317");
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nmtuk6b6c {
  d: path("M15.736 23.56c-1.43 0-2.587-1.067-2.587-2.386v-2.821c0-1.32 1.157-2.387 2.587-2.387s2.587 1.067 2.587 2.387v2.82c0 1.32-1.156 2.387-2.587 2.387");
}

.nr1w56t5z {
  cx: 12.422px;
  cy: 12.691px;
  rx: 0.526px;
  ry: 0.266px;
}

.nwtv201rg {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("M17.875 9.825a.375.375 0 0 0-.037.529c.37.426.865.685 1.319.836s.898.205 1.202.199a.375.375 0 0 0-.015-.75a3 3 0 0 1-.95-.16c-.375-.125-.735-.325-.99-.617a.375.375 0 0 0-.529-.037");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pb6-h6b6v {
  stop-color: var(--svg-color--7052bb, #7052BB);
  stop-opacity: 0;
}

.pj__wrb2a {
  stop-color: var(--svg-color--b36d8d, #B36D8D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp7rrkbql {
  d: path("M9.433 15.078a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.q06k5hbty {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.83 4.79c.032.329.318 1.563.737 2.31");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qz1bsbh9m {
  stop-color: var(--svg-color--776299, #776299);
  stop-opacity: 0;
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rl0j2vb6c {
  fill: var(--svg-color--383034, #383034);
  d: path("M17.279 12.858c.358-.63.903-1.128 2.076-1.128c.514 0 1.01.142 1.45.498c.363.293.314.669.033.81l-.751.428c-.88-.285-1.854-.323-2.808-.608");
}

.s2s91xb1y {
  stop-color: var(--svg-color--7a55aa, #7A55AA);
}

.s3m8e5eat {
  stop-color: var(--svg-color--dea69a, #DEA69A);
}

.s91tejbjx {
  d: path("M19.76 13.223a1.14 1.14 0 0 0-.312-.625l-.351.385l.158.308z");
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.t6jqthc7h {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M9.433 15.078a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tc99wkbfq {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M20.352 11.014c-.521.01-1.606-.188-2.23-.906");
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.ue2icdbry {
  d: path("M9.125 5.504c.84-.747 2.05-.755 2.729-.634l.543 1.743c-.347-.053-.657.068-.917.317c-.616 1.703-2.732 2.641-3.713 2.898c-.204-2.015-.09-3.034 1.358-4.324");
}

.uea4-671p {
  stop-color: var(--svg-color--776299, #776299);
}

.ugfjl15nl {
  stop-color: var(--svg-color--dea69a, #DEA69A);
  stop-opacity: 0;
}

.up50vjm_w {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.507 11.809c-.883 0-1.628.608-1.83 1.43a.37.37 0 0 0 .361.46h3.014a.31.31 0 0 0 .307-.367a1.89 1.89 0 0 0-1.852-1.523");
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v-qwllbxk {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M16.918 18.267c-.958-.557-1.98-.231-2.36-.002a.275.275 0 1 1-.284-.471c.484-.291 1.729-.695 2.92-.002a.275.275 0 0 1-.276.475");
}

.vrfgrpb3q {
  d: path("M9.407 15.8a2.173 2.173 0 1 0 0-4.347a2.173 2.173 0 0 0 0 4.347");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wq2ua4b3u {
  d: path("M12.786 12.176a1.206 1.206 0 0 0-1.162 1.523h2.33q.042-.155.043-.317a1.214 1.214 0 0 0-1.21-1.206");
}

.wycv0qbje {
  d: path("m15.22 13.14l-.718 2.295a.728.728 0 0 0 .703.945h1.062a.73.73 0 0 0 .704-.945l-.718-2.296c-.154-.509-.872-.509-1.033 0");
}

.x37z32b5t {
  fill: var(--svg-color--000, #000);
  d: path("M17.996 13.382c0-.384.307-.69.69-.69a.688.688 0 0 1 .614 1.007h-1.222a.6.6 0 0 1-.082-.317");
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xl55yte0p {
  cx: 12.422px;
  cy: 12.691px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.526px;
  ry: 0.266px;
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
