<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iU8WNfc)"><path fill="url(#iOxEQ1c)" class="ne-69mqpm"/></g><g filter="url(#iJgfsTc)"><path fill="url(#ifYlLze)" class="rhyr5j2qw"/><path fill="url(#imgOIec)" class="rhyr5j2qw"/></g><g filter="url(#iogbsKD)"><path class="p36woq6iy"/><path fill="url(#iLZ87He)" class="x0ehr0bsp"/></g><g filter="url(#iR3v6ub)"><path class="h79l1brrp"/><path fill="url(#i1BTREe)" class="n2ykrmb3r"/></g><g filter="url(#iCO6nxb)"><path fill="url(#igRTBde)" class="dercbjb8y"/><path fill="url(#icr2Evj)" class="dercbjb8y"/><path fill="url(#ivvCihc)" class="dercbjb8y"/><path fill="url(#ikk880y)" class="dercbjb8y"/><path fill="url(#ijyc6Xd)" class="dercbjb8y"/><path fill="url(#iGSms6c)" class="dercbjb8y"/><path fill="url(#i4xnfIc)" class="dercbjb8y"/><path fill="url(#i52xAue)" class="dercbjb8y"/></g><path fill="url(#ioIGPvc)" class="dercbjb8y"/><path fill="url(#iqkzJNc)" class="dercbjb8y"/><path fill="url(#ipxgS9b)" class="dercbjb8y"/><g filter="url(#iHzCFeb)"><path class="xrofv2bpm"/></g><g filter="url(#iOCpWXb)"><path class="tqliayuii"/><path fill="url(#iP8zFzd)" class="hdjr5zr7e"/><path fill="url(#iIXUoDc)" class="hdjr5zr7e"/><path fill="url(#idD6bed)" class="hdjr5zr7e"/><path fill="url(#iriLsmx)" class="hdjr5zr7e"/></g><g filter="url(#ixYtUbe)"><path stroke="url(#i6ybN7b)" class="t5exzhb6l"/></g><path class="xemv9qbrn"/><g filter="url(#iTQfxRF)"><path class="z42bd1bux"/></g><g filter="url(#iiBi12d)"><path class="ghjsgxb_p"/></g><g filter="url(#iGxPXBQ)"><path class="x5zq1i05f"/></g><g filter="url(#ivv118D)"><path clip-rule="evenodd" class="grtkm-npv"/></g><path class="yk0g75bne"/><path fill="url(#ivFOLoc)" class="s8-w646nr"/><path class="p0seidbnb"/><g filter="url(#iXoWlLe)"><path class="fby__nbpw"/><path fill="url(#iKtziue)" class="wmnxdlbvw"/></g><g filter="url(#iYLJrWh)"><path fill="url(#iuYbX2b)" class="tjp18e4hk"/></g><path class="ut6ru52ad"/><path fill="url(#iksKqie)" class="gzjb0abtm"/><path class="z4zz2wbrq"/><g filter="url(#iXQnAsc)"><path fill="url(#iYibl5b)" class="ip5hchb0y"/></g><g filter="url(#iGXylPc)"><ellipse transform="rotate(-27.914 11.2 17.302)" class="t6dlcjbjr"/><ellipse fill="url(#i4L9Rjc)" transform="rotate(-27.914 11.2 17.302)" class="g6lmyu7wo"/></g><g filter="url(#iu5Jzyb)"><path class="r62keph2k"/></g><g filter="url(#iS31hFS)"><path class="b9w1mdb-f"/></g><path fill="url(#iCup87J)" class="e9a_4yu5t"/><path fill="url(#iRzEZkv)" class="e9a_4yu5t"/><path fill="url(#im9IZcd)" class="e9a_4yu5t"/><g filter="url(#iHXaRKd)"><path fill="url(#iXNIVqb)" class="djextidzg"/><path fill="url(#ilfT6hb)" class="djextidzg"/></g><g filter="url(#iUONgrb)"><path fill="url(#igxpzny)" class="oyyl-7btf"/></g><path fill="url(#iCvaDCb)" class="oyyl-7btf"/><path fill="url(#iD35BOP)" class="oyyl-7btf"/><path fill="url(#irXmuve)" class="oyyl-7btf"/><g filter="url(#igpoXmc)"><path fill="url(#iv69enI)" class="vh7um2wbk"/></g><path fill="url(#ikgmtnd)" class="vh7um2wbk"/><path fill="url(#i5pIzpd)" class="vh7um2wbk"/><path fill="url(#ifrssQe)" class="vh7um2wbk"/><path fill="url(#isPyjsb)" class="vh7um2wbk"/><path fill="url(#i15zGac)" class="vh7um2wbk"/><g filter="url(#i8YL6KX)"><path fill="url(#isyBL6i)" class="lqvl9n_nn"/><path fill="url(#iySawCu)" class="lqvl9n_nn"/><path fill="url(#iC8mcSd)" class="lqvl9n_nn"/><path fill="url(#iRxVvOc)" class="lqvl9n_nn"/><path fill="url(#im9OVxk)" class="lqvl9n_nn"/></g><g filter="url(#iyATVEB)"><path fill="url(#iJvo7Db)" class="mpvu2pb2g"/></g><path fill="url(#iAKGKec)" class="mpvu2pb2g"/><path fill="url(#iSFLjhd)" class="mpvu2pb2g"/><defs><radialGradient id="ifYlLze" cx="0" cy="0" r="1" gradientTransform="matrix(4.73361 -2.15165 2.62706 5.77951 23.548 19.454)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="imgOIec" cx="0" cy="0" r="1" gradientTransform="matrix(2.50228 1.40256 -.39652 .70743 25.508 15.422)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iLZ87He" cx="0" cy="0" r="1" gradientTransform="matrix(2.87147 -.2136 .16697 2.24469 24.217 18.833)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="i1BTREe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.29508 0 0 -1.81054 7.115 18.62)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="igRTBde" cx="0" cy="0" r="1" gradientTransform="matrix(-12.36831 5.70344 -7.63394 -16.55474 21.303 17.597)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="icr2Evj" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 7.499 11.787)scale(4.29038 2.98775)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="ivvCihc" cx="0" cy="0" r="1" gradientTransform="matrix(2.04151 -6.6107 8.38775 2.5903 11.72 30.496)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="ikk880y" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52535 12.93205 -13.00127 -1.53351 16.892 17.895)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="ijyc6Xd" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.4887 -12.5556 0 15.367 18.339)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="iGSms6c" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.639 11.383)scale(13.3835 23.0423)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="i4xnfIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.1885 2.68589 0 20.242 16.801)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="i52xAue" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4961 2.8607 0 11.916 16.367)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="ioIGPvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.1875 -3.41528 0 25.431 14.964)" gradientUnits="userSpaceOnUse"><stop class="tmabph10y"/><stop offset="1" class="pmn3c8cra"/></radialGradient><radialGradient id="iqkzJNc" cx="0" cy="0" r="1" gradientTransform="rotate(131.403 7.804 9.483)scale(7.74924 5.184)" gradientUnits="userSpaceOnUse"><stop class="ah1agj4tq"/><stop offset="1" class="pzvyv6bhs"/></radialGradient><radialGradient id="ipxgS9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.4465 -12.4709 0 15.862 14.526)" gradientUnits="userSpaceOnUse"><stop offset=".926" class="pxj-7bb3u"/><stop offset="1" class="rkqsu1bpg"/></radialGradient><radialGradient id="iP8zFzd" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 17.101 3.549)scale(3.98261 1.22741)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iriLsmx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48224 0 0 -.4144 16.901 21.415)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="ivFOLoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54294 -2.45421 0 20.015 17.484)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iKtziue" cx="0" cy="0" r="1" gradientTransform="matrix(-.44105 -.56836 .78249 -.60722 19.581 17.644)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iksKqie" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54295 -2.45423 0 11.715 17.484)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i4L9Rjc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.397 3.452)scale(.9397 1.12956)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iCup87J" cx="0" cy="0" r="1" gradientTransform="matrix(-.84218 3.75478 -8.78476 -1.97039 25.881 5.054)" gradientUnits="userSpaceOnUse"><stop class="s6vdf8bty"/><stop offset=".789" class="lxkykv_ud"/></radialGradient><radialGradient id="iRzEZkv" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 .53125 -1.15317 4.54483 20.347 6.687)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="q2rl-9b2o"/><stop offset="1" class="fi285-b6u"/></radialGradient><radialGradient id="im9IZcd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -2.625 6.33197 3.61827 22.284 10.531)" gradientUnits="userSpaceOnUse"><stop class="p6ygghbxv"/><stop offset="1" class="ih_njzbst"/></radialGradient><radialGradient id="iXNIVqb" cx="0" cy="0" r="1" gradientTransform="matrix(.17188 2.91016 -14.53547 .85847 21.253 2.027)" gradientUnits="userSpaceOnUse"><stop class="nsg0945ca"/><stop offset="1" class="mcdrc7blw"/></radialGradient><radialGradient id="ilfT6hb" cx="0" cy="0" r="1" gradientTransform="matrix(1.45313 0 0 5.1925 20.8 3.344)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="w7pk8_-qm"/><stop offset="1" class="wfm74pxcd"/></radialGradient><radialGradient id="iCvaDCb" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 1.71875 -3.03125 4.35398 17.69 9.062)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="hc5vad6zv"/><stop offset="1" class="m71s56bwv"/></radialGradient><radialGradient id="iD35BOP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.93844 1.49148 0 24.653 14.511)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="b5m4mk31i"/><stop offset="1" class="o02xvvb7n"/></radialGradient><radialGradient id="irXmuve" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 0 0 .30337 18.753 8.687)" gradientUnits="userSpaceOnUse"><stop class="w98e9_6zv"/><stop offset="1" class="phr-zrige"/></radialGradient><radialGradient id="iv69enI" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28125 -.09372 .19553 -8.93238 21.565 5.594)" gradientUnits="userSpaceOnUse"><stop class="qnoj66lkr"/><stop offset="1" class="s_fkwccyi"/></radialGradient><radialGradient id="ikgmtnd" cx="0" cy="0" r="1" gradientTransform="matrix(11.55068 3.52232 -4.80864 15.76891 9.13 5.748)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="rjs9uccph"/><stop offset=".952" class="x7ia8vuzd"/></radialGradient><radialGradient id="i5pIzpd" cx="0" cy="0" r="1" gradientTransform="matrix(1.11064 -4.72815 1.61144 .37853 16.84 4.605)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="zz39r5b3o"/><stop offset="1" class="wvn8vtban"/></radialGradient><radialGradient id="ifrssQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.06346 1.33277 -6.75892 -.32185 9.193 7.398)" gradientUnits="userSpaceOnUse"><stop class="biviy7bfr"/><stop offset="1" class="ednzh9b6g"/></radialGradient><radialGradient id="isPyjsb" cx="0" cy="0" r="1" gradientTransform="matrix(-13.48639 2.82409 -3.69438 -17.64244 17.539 7.525)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="rq033_icj"/><stop offset="1" class="dbmxbxbzy"/></radialGradient><radialGradient id="i15zGac" cx="0" cy="0" r="1" gradientTransform="matrix(.88851 -3.93483 2.3195 .52376 6.94 14.506)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="nmcqtrbfm"/><stop offset="1" class="w9crknafl"/></radialGradient><radialGradient id="isyBL6i" cx="0" cy="0" r="1" gradientTransform="rotate(137.988 8.551 4.646)scale(9.89862 9.45071)" gradientUnits="userSpaceOnUse"><stop class="rnyxtsb4p"/><stop offset="1" class="isvyw7ooh"/></radialGradient><radialGradient id="iySawCu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -4.75 18.44 3.5)" gradientUnits="userSpaceOnUse"><stop class="dqjzd9_8e"/><stop offset="1" class="jcrjf-b8x"/></radialGradient><radialGradient id="iRxVvOc" cx="0" cy="0" r="1" gradientTransform="matrix(5.90625 .125 -.02777 1.31192 10.128 4.125)" gradientUnits="userSpaceOnUse"><stop class="qw_ssccar"/><stop offset="1" class="mvpyyqb8k"/></radialGradient><radialGradient id="im9OVxk" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -.09375 .17757 2.4268 14.128 2.469)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jdd1i0reo"/><stop offset="1" class="ixxpbv8hf"/></radialGradient><radialGradient id="iJvo7Db" cx="0" cy="0" r="1" gradientTransform="matrix(-8.06249 1.65631 -3.03846 -14.79042 14.534 2.594)" gradientUnits="userSpaceOnUse"><stop class="nsmntj3ul"/><stop offset="1" class="q9wqsddqp"/></radialGradient><radialGradient id="iAKGKec" cx="0" cy="0" r="1" gradientTransform="matrix(8.03125 .96875 -1.11478 9.24187 7.253 3.25)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="atp4gmb-q"/><stop offset="1" class="qfleuzzqm"/></radialGradient><radialGradient id="iSFLjhd" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 -2.3259 1.71042 1.99932 4.596 7.763)" gradientUnits="userSpaceOnUse"><stop class="lo97d1z0q"/><stop offset="1" class="qt9c-0dps"/></radialGradient><filter id="iU8WNfc" width="6.27" height="6.12" x="3.894" y="15.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/></filter><filter id="iJgfsTc" width="6.12" height="6.37" x="21.986" y="15.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/></filter><filter id="iogbsKD" width="5.085" height="5.085" x="22.503" y="16.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3097" stdDeviation=".25"/></filter><filter id="iR3v6ub" width="4.585" height="4.585" x="4.698" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3097" stdDeviation=".125"/></filter><filter id="iCO6nxb" width="19.139" height="19.458" x="6.292" y="10.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/></filter><filter id="iHzCFeb" width="4.57" height="6.1" x="13.272" y="17.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3097" stdDeviation=".25"/></filter><filter id="iOCpWXb" width="4.07" height="5.6" x="13.83" y="17.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3097" stdDeviation=".125"/></filter><filter id="ixYtUbe" width="6.68" height="2.541" x="12.525" y="23.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3097" stdDeviation=".05"/></filter><filter id="iTQfxRF" width="5.528" height="2.445" x="17.837" y="15.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/></filter><filter id="iiBi12d" width="5.528" height="2.445" x="8.366" y="15.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/></filter><filter id="iGxPXBQ" width="4.484" height="1.895" x="8.623" y="13.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/></filter><filter id="ivv118D" width="4.484" height="1.895" x="18.925" y="13.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/></filter><filter id="iXoWlLe" width="1.316" height="1.144" x="18.709" y="16.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3097" stdDeviation=".05"/></filter><filter id="iYLJrWh" width="1.334" height="1.376" x="20.396" y="16.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3097" stdDeviation=".1"/></filter><filter id="iXQnAsc" width="1.515" height="1.618" x="11.947" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3097" stdDeviation=".1"/></filter><filter id="iGXylPc" width="1.556" height="1.159" x="10.421" y="16.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3097" stdDeviation=".05"/></filter><filter id="iu5Jzyb" width="3.958" height="1.518" x="19.154" y="13.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3097" stdDeviation=".1"/></filter><filter id="iS31hFS" width="3.958" height="1.518" x="8.786" y="13.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3097" stdDeviation=".1"/></filter><filter id="iHXaRKd" width="7.307" height="5.168" x="20.417" y="1.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.8 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/></filter><filter id="iUONgrb" width="12.925" height="6.714" x="14.465" y="8.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.992157 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.560784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3097" result="effect2_innerShadow_4002_3097"/></filter><filter id="igpoXmc" width="17.006" height="13.059" x="4.107" y="1.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.45098 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/></filter><filter id="i8YL6KX" width="13.757" height="8.679" x="4.257" y="1.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.588235 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/></filter><filter id="iyATVEB" width="10.523" height="5.986" x="4.357" y="1.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.619608 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3097"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.701961 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3097" result="effect2_innerShadow_4002_3097"/></filter><linearGradient id="iOxEQ1c" x1="3.894" x2="9.522" y1="18.785" y2="18.785" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iIXUoDc" x1="14.08" x2="15.865" y1="21.151" y2="21.151" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="idD6bed" x1="15.865" x2="15.865" y1="22.67" y2="21.51" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="i6ybN7b" x1="13.841" x2="14.718" y1="25.351" y2="23.997" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iuYbX2b" x1="21.494" x2="20.898" y1="17.586" y2="17.954" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYibl5b" x1="13.13" x2="12.533" y1="17.586" y2="17.954" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igxpzny" x1="26.159" x2="15.409" y1="13.594" y2="13.594" gradientUnits="userSpaceOnUse"><stop class="qxbo6kk2p"/><stop offset="1" class="kkvh--b-a"/></linearGradient><linearGradient id="iC8mcSd" x1="4.357" x2="8.534" y1="9.562" y2="8.594" gradientUnits="userSpaceOnUse"><stop class="d2rffhbfx"/><stop offset="1" class="m1v3gnbun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-wearing-turban-dark" /></template>
<style>
.ah1agj4tq {
  stop-color: var(--svg-color--655352, #655352);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.atp4gmb-q {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
  stop-opacity: 0;
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b5m4mk31i {
  stop-color: var(--svg-color--b384b3, #B384B3);
}

.b9w1mdb-f {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.344 14.107c-.613-.15-2.138-.074-3.158.655");
}

.biviy7bfr {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d2rffhbfx {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
}

.dbmxbxbzy {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
}

.dercbjb8y {
  d: path("m6.292 14.82l.021.016l-.001-.166c-.007-.59-.02-1.727.477-2.47c.801-1.196 1.711-1.285 2.601-1.285h12.96c2.465 0 3.081 1.796 3.081 2.694l-.073.9l-.028.103v6.452c-.235 5.33-4.397 8.909-9.477 8.909s-9.243-3.579-9.477-8.909z");
}

.djextidzg {
  d: path("m20.417 2.027l.055 2.427c1.224-.03 3.562.083 5.578 1.227c.85.482 1.29.993 1.574 1.414c-.073-.97-.366-1.894-1.202-3.047c-.979-1.35-2.795-2.02-4.42-2.02z");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dqjzd9_8e {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9a_4yu5t {
  d: path("M4.552 10.655c.193 2.807 1.397 3.89 1.761 4.18c0-.514-.074-1.815.476-2.635c.801-1.196 1.711-1.285 2.601-1.285h12.96c2.465 0 3.081 1.796 3.081 2.694l-.093 1.145c.217 0 .866-.236 1.115-.727c.65-1.285 1.068-3.964 1.161-5.528s.031-2.764-1.192-4.451c-.979-1.35-2.795-2.02-4.42-2.02H10.45c-3.712 0-4.678 1.406-5.42 2.799c-.594 1.114-.675 2.201-.674 2.843c0 .76.012 2.129.195 2.985");
}

.ednzh9b6g {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
  stop-opacity: 0;
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fby__nbpw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.894 16.935c.12.162-.132.36-.42.574c-.287.215-.5.366-.62.204c-.122-.161.013-.466.3-.681c.288-.215.62-.258.74-.097");
}

.fi285-b6u {
  stop-color: var(--svg-color--ece8f1, #ECE8F1);
  stop-opacity: 0;
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.g6lmyu7wo {
  cx: 11.2px;
  cy: 17.302px;
  rx: 0.741px;
  ry: 0.375px;
}

.ghjsgxb_p {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.694 17.537c-.505-.888-1.273-1.589-2.924-1.589c-.723 0-1.42.2-2.04.701c-.512.413-.443.942-.047 1.14l1.057.604c1.24-.401 2.61-.455 3.954-.856");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.grtkm-npv {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m22.962 14.368l-.262.437za.51.51 0 0 1-.524.875l-.01-.005a3 3 0 0 0-.214-.11a5 5 0 0 0-.651-.258c-.552-.176-1.28-.308-2.039-.174a.51.51 0 0 1-.177-1.005c.976-.172 1.88.001 2.526.208a6 6 0 0 1 1 .42q.04.02.062.033l.018.01l.006.004l.002.001");
}

.gzjb0abtm {
  d: path("M11.712 16.576a1.697 1.697 0 0 0-1.636 2.145h3.279q.059-.218.061-.447a1.71 1.71 0 0 0-1.705-1.698");
}

.h79l1brrp {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M6.99 20.662a2.043 2.043 0 1 0 0-4.086a2.043 2.043 0 0 0 0 4.086");
}

.hc5vad6zv {
  stop-color: var(--svg-color--bfb1c9, #BFB1C9);
}

.hdjr5zr7e {
  d: path("m15.138 17.932l-1.01 3.233c-.207.665.288 1.33.99 1.33h1.495c.701 0 1.196-.675.99-1.33l-1.01-3.233c-.217-.716-1.228-.716-1.455 0");
}

.ih_njzbst {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
  stop-opacity: 0;
}

.ip5hchb0y {
  d: path("M13.262 18.074c0-.548-.446-.914-.567-1.024l-.548.53l.338.687z");
}

.isvyw7ooh {
  stop-color: var(--svg-color--c0bbc4, #C0BBC4);
}

.ixxpbv8hf {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
  stop-opacity: 0;
}

.jcrjf-b8x {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
  stop-opacity: 0;
}

.jdd1i0reo {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
}

.kkvh--b-a {
  stop-color: var(--svg-color--ddd6e4, #DDD6E4);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo97d1z0q {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
}

.lqvl9n_nn {
  d: path("M4.542 10.606c.457-.912 1.614-2.206 5.677-2.626c.406-.042 1.003-.06 1.672-.08c1.666-.05 3.775-.113 4.482-.593c.933-.445 1.973-3.245 1.54-5.28h-5.97L4.954 4.976c-.524 1.061-.598 2.08-.597 2.694c0 .745.012 2.077.185 2.936");
}

.lxkykv_ud {
  stop-color: var(--svg-color--ebe6f2, #EBE6F2);
}

.m1v3gnbun {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
  stop-opacity: 0;
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.m71s56bwv {
  stop-color: var(--svg-color--e0dae8, #E0DAE8);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcdrc7blw {
  stop-color: var(--svg-color--fafafa, #FAFAFA);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mpvu2pb2g {
  d: path("M4.357 7.763c.557-.67 1.563-1.613 2.897-1.973c1.879-.51 4.836-.733 6.069-.821c.45.026 1.556-.441 1.556-1.61c0-.433-.016-.89-.053-1.332H10.45c-3.712 0-4.678 1.407-5.42 2.8c-.594 1.114-.675 2.201-.674 2.843z");
}

.mvpyyqb8k {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
  stop-opacity: 0;
}

.n2ykrmb3r {
  d: path("M6.99 20.662a2.043 2.043 0 1 0 0-4.086a2.043 2.043 0 0 0 0 4.086");
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.ne-69mqpm {
  d: path("M6.954 21.68a3.06 3.06 0 1 0 0-6.121a3.06 3.06 0 0 0 0 6.12");
}

.nmcqtrbfm {
  stop-color: var(--svg-color--a87b9c, #A87B9C);
}

.nsg0945ca {
  stop-color: var(--svg-color--dbdbdc, #DBDBDC);
}

.nsmntj3ul {
  stop-color: var(--svg-color--d2d1d3, #D2D1D3);
}

.o02xvvb7n {
  stop-color: var(--svg-color--b384b3, #B384B3);
  stop-opacity: 0;
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oyyl-7btf {
  d: path("M26.99 12.495c.005-1.482-1.085-2.607-1.93-3.105c-1.34-.79-3.268-1.004-4.104-.999H19.47l-4.955.805l.256 1.719h7.579c2.465 0 3.102 1.792 3.043 2.694l-.055 1.146c.217 0 .866-.237 1.115-.728c.203-.4.383-.937.537-1.532");
}

.p0seidbnb {
  fill: var(--svg-color--000, #000);
  d: path("M19.047 18.274c0-.54.432-.973.972-.973s.972.433.972.973a.96.96 0 0 1-.108.447h-1.72a.9.9 0 0 1-.116-.447");
}

.p36woq6iy {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M25.046 20.662a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.p6ygghbxv {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
}

.phr-zrige {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
  stop-opacity: 0;
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmn3c8cra {
  stop-color: var(--svg-color--553835, #553835);
  stop-opacity: 0;
}

.pxj-7bb3u {
  stop-color: var(--svg-color--422742, #422742);
  stop-opacity: 0;
}

.pzvyv6bhs {
  stop-color: var(--svg-color--655352, #655352);
  stop-opacity: 0;
}

.q2rl-9b2o {
  stop-color: var(--svg-color--cfcad4, #CFCAD4);
}

.q9wqsddqp {
  stop-color: var(--svg-color--b5b4b6, #B5B4B6);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qfleuzzqm {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qnoj66lkr {
  stop-color: var(--svg-color--f5f4f6, #F5F4F6);
}

.qt9c-0dps {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw_ssccar {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
}

.qxbo6kk2p {
  stop-color: var(--svg-color--eee8f4, #EEE8F4);
}

.r62keph2k {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.554 14.107c.613-.15 2.139-.074 3.158.655");
}

.rhyr5j2qw {
  d: path("M25.046 21.68a3.06 3.06 0 1 0 0-6.121a3.06 3.06 0 0 0 0 6.12");
}

.rjs9uccph {
  stop-color: var(--svg-color--d1cad9, #D1CAD9);
  stop-opacity: 0;
}

.rkqsu1bpg {
  stop-color: var(--svg-color--5e4964, #5E4964);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rnyxtsb4p {
  stop-color: var(--svg-color--ddddde, #DDDDDE);
}

.rq033_icj {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
  stop-opacity: 0;
}

.s_fkwccyi {
  stop-color: var(--svg-color--cfc8d7, #CFC8D7);
}

.s6vdf8bty {
  stop-color: var(--svg-color--f8f6fb, #F8F6FB);
}

.s8-w646nr {
  d: path("M20.019 16.576a1.697 1.697 0 0 1 1.636 2.145h-3.28a1.7 1.7 0 0 1-.061-.447c0-.934.764-1.698 1.705-1.698");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t5exzhb6l {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.865 24.156c-.99 0-1.921-.238-2.703-.655c-.268-.14-.555.168-.387.417a3.67 3.67 0 0 0 3.09 1.688a3.67 3.67 0 0 0 3.09-1.688c.168-.259-.119-.557-.386-.418a5.7 5.7 0 0 1-2.704.656Z");
}

.t6dlcjbjr {
  cx: 11.2px;
  cy: 17.302px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.741px;
  ry: 0.375px;
}

.tjp18e4hk {
  d: path("M21.53 18.05a1.6 1.6 0 0 0-.44-.88l-.494.543l.224.434z");
}

.tmabph10y {
  stop-color: var(--svg-color--553835, #553835);
}

.tqliayuii {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.138 17.932l-1.01 3.233c-.207.665.288 1.33.99 1.33h1.495c.701 0 1.196-.675.99-1.33l-1.01-3.233c-.217-.716-1.228-.716-1.455 0");
}

.ut6ru52ad {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.318 16.06a2.656 2.656 0 0 0-2.577 2.013a.52.52 0 0 0 .51.648h4.243c.27 0 .486-.247.432-.517a2.665 2.665 0 0 0-2.608-2.145");
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vh7um2wbk {
  d: path("M20.946 2.027c.357 1.961.193 4.541-1.02 6.426c-.921 1.433-2.18 2.462-3.472 2.462H9.39c-.89 0-1.8.089-2.6 1.285c-.499.743-.485 1.88-.478 2.47l.001.166c-.364-.29-1.568-1.375-1.761-4.18c-.183-.857-.195-2.227-.195-2.986c0-.642.08-1.729.673-2.843c.743-1.393 1.71-2.8 5.42-2.8z");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w7pk8_-qm {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
}

.w98e9_6zv {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
}

.w9crknafl {
  stop-color: var(--svg-color--a87b9c, #A87B9C);
  stop-opacity: 0;
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wfm74pxcd {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
  stop-opacity: 0;
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wmnxdlbvw {
  d: path("M19.894 16.935c.12.162-.132.36-.42.574c-.287.215-.5.366-.62.204c-.122-.161.013-.466.3-.681c.288-.215.62-.258.74-.097");
}

.wvn8vtban {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x0ehr0bsp {
  d: path("M25.046 20.662a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.x5zq1i05f {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m9.404 15.238l-.008.005h-.001a.51.51 0 0 1-.524-.875h.001l.002-.002l.006-.003l.018-.01q.021-.014.061-.035q.08-.043.22-.112c.188-.089.455-.203.78-.307c.647-.207 1.551-.38 2.527-.208a.51.51 0 1 1-.177 1.005c-.759-.134-1.487-.002-2.039.175a5 5 0 0 0-.866.367");
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.x7ia8vuzd {
  stop-color: var(--svg-color--f1edf4, #F1EDF4);
}

.xemv9qbrn {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M15.865 24.156c-.99 0-1.921-.238-2.703-.655c-.268-.14-.555.168-.387.417a3.67 3.67 0 0 0 3.09 1.688a3.67 3.67 0 0 0 3.09-1.688c.168-.259-.119-.557-.386-.418a5.7 5.7 0 0 1-2.704.656");
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xrofv2bpm {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.119 18.196l-1.3 3.233c-.206.665.289 1.33.99 1.33h1.496c.7 0 1.196-.676.99-1.33l-1.011-3.233c-.217-.717-.938-.717-1.165 0");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.yk0g75bne {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.412 16.06c1.242 0 2.292.856 2.577 2.013a.52.52 0 0 1-.51.648h-4.242a.438.438 0 0 1-.432-.517a2.66 2.66 0 0 1 2.607-2.145");
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z42bd1bux {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M18.037 17.537c.505-.888 1.272-1.589 2.924-1.589c.723 0 1.42.2 2.04.701c.511.413.443.942.047 1.14l-1.057.604c-1.24-.401-2.61-.455-3.954-.856");
}

.z4zz2wbrq {
  fill: var(--svg-color--000, #000);
  d: path("M12.684 18.274a.97.97 0 0 0-.972-.973a.97.97 0 0 0-.972.973a.95.95 0 0 0 .108.447h1.72a.96.96 0 0 0 .116-.447");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zz39r5b3o {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
}

</style>
