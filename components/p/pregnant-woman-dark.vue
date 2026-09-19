<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVfn2yb)"><path fill="url(#iMA5dRm)" clip-rule="evenodd" class="lh8aekx1o"/><path fill="url(#iVV4Xqd)" clip-rule="evenodd" class="lh8aekx1o"/><path fill="url(#inK9nad)" clip-rule="evenodd" class="lh8aekx1o"/><path fill="url(#iJyrkyc)" clip-rule="evenodd" class="lh8aekx1o"/><path fill="url(#inDP7Fe)" clip-rule="evenodd" class="lh8aekx1o"/><path fill="url(#iIEazTd)" clip-rule="evenodd" class="lh8aekx1o"/><path fill="url(#il0bmTb)" clip-rule="evenodd" class="lh8aekx1o"/><path fill="url(#iAzOGYb)" clip-rule="evenodd" class="lh8aekx1o"/><path fill="url(#idZqOsd)" clip-rule="evenodd" class="lh8aekx1o"/><path fill="url(#ivFzqMb)" clip-rule="evenodd" class="lh8aekx1o"/><path fill="url(#im7mQcF)" clip-rule="evenodd" class="lh8aekx1o"/><path fill="url(#i7KN3ce)" clip-rule="evenodd" class="lh8aekx1o"/></g><g filter="url(#ibReF5d)"><path fill="url(#i6n3psd)" class="jloy9jwlq"/><path fill="url(#ieoR1ac)" class="jloy9jwlq"/><path fill="url(#iv3GZpc)" class="jloy9jwlq"/><path fill="url(#iv5mtxG)" class="jloy9jwlq"/><path fill="url(#i0ILhtd)" class="jloy9jwlq"/><path fill="url(#iTOeiCe)" class="jloy9jwlq"/><path fill="url(#icUTm6n)" class="jloy9jwlq"/><path fill="url(#iUE5chd)" class="jloy9jwlq"/></g><g filter="url(#if9cLYb)"><path fill="url(#i8WKeKc)" class="q0ib_xk4x"/></g><g filter="url(#iY3Tqfc)"><path class="trugahbpj"/></g><path fill="url(#i7V47Fd)" class="xs7bh_47t"/><path fill="url(#ilsoP7B)" class="xs7bh_47t"/><g filter="url(#iKCTp2c)"><path fill="url(#ijYBLRv)" class="smds5mbqf"/></g><g filter="url(#iTDMaXb)"><path fill="url(#iw6XB4b)" class="b_1v1rb3o"/></g><g filter="url(#iXOShDd)"><path stroke="url(#iMrD4eb)" class="haf370ocm"/></g><g filter="url(#iHn1T6d)"><path stroke="url(#iYRpZcd)" class="ibiyjmt2x"/></g><g filter="url(#iN6ASKc)"><path stroke="url(#iX7E2De)" class="xx4jetbse"/></g><path fill="url(#iZEsuVb)" class="cp_ktim0y"/><path fill="url(#igEvI8q)" class="zt2nfysbf"/><g filter="url(#iDJvnIc)"><path fill="url(#i3e5krc)" class="zi5e98b5e"/></g><g filter="url(#i3UGF5c)"><path fill="url(#iue24wd)" class="f4sgag53f"/><path fill="url(#i5JvI2d)" class="f4sgag53f"/></g><g filter="url(#iCJz6we)"><path class="gsrv7ubtl"/><path fill="url(#ib4B4rd)" class="m539_vbau"/></g><g filter="url(#iOBXqye)"><path class="xuhwwnbiu"/><path fill="url(#imPMIKe)" class="e09eu8bna"/></g><g filter="url(#ioJGHGA)"><path fill="url(#iw1gDGe)" class="n4l00c1xr"/><path fill="url(#ivZ9QDe)" class="n4l00c1xr"/><path fill="url(#ieVvjfb)" class="n4l00c1xr"/><path fill="url(#iqGwKyd)" class="n4l00c1xr"/><path fill="url(#iSkp4ud)" class="n4l00c1xr"/><path fill="url(#i9sRLWb)" class="n4l00c1xr"/><path fill="url(#ilu0X9c)" class="n4l00c1xr"/><path fill="url(#iMRYPnb)" class="n4l00c1xr"/></g><path fill="url(#ihQ2bId)" class="n4l00c1xr"/><path fill="url(#iUC6hsd)" class="n4l00c1xr"/><g filter="url(#iVIluFY)"><path class="xvhp6rcuw"/></g><g filter="url(#i6ghJGX)"><path class="esboituev"/><path fill="url(#iGIFwXG)" class="yusrdebwv"/><path fill="url(#iDIobzc)" class="yusrdebwv"/><path fill="url(#i04J3Rb)" class="yusrdebwv"/><path fill="url(#iqSBRAe)" class="yusrdebwv"/></g><g filter="url(#i41NUAe)"><path stroke="url(#iShl9zb)" class="a403usbll"/></g><path class="mezfmvbmf"/><g filter="url(#it1jZMd)"><path class="s5d7bhbfb"/></g><g filter="url(#itOqRvN)"><path class="lg5pgtyig"/></g><g filter="url(#iV20zPe)"><path class="m6pycabqr"/></g><g filter="url(#iGxlXhd)"><path clip-rule="evenodd" class="wc4eq0bch"/></g><path class="pq6t-dhpn"/><path fill="url(#iU01Hob)" class="ajxjvpbbc"/><path class="mbv_48bws"/><g filter="url(#islMrye)"><path class="gi5elwbsw"/><path fill="url(#ixLJVab)" class="i_ru-mbhh"/></g><g filter="url(#i2WJeQe)"><path fill="url(#i5VSctd)" class="hefkts3ys"/></g><path class="t3qqjcb3f"/><path fill="url(#i94zjic)" class="kuk58bcae"/><path class="j1bn99p7h"/><g filter="url(#iR0P7Wd)"><path fill="url(#ipO19ck)" class="d5nkjk5vc"/></g><g filter="url(#i0EkZMd)"><ellipse transform="rotate(-27.914 16.065 8.886)" class="wn-fsabnt"/><ellipse fill="url(#iZO2N2L)" transform="rotate(-27.914 16.065 8.886)" class="co4ddab0u"/></g><g filter="url(#iI3yxfd)"><path class="dta2yqblg"/></g><g filter="url(#iEfSE8d)"><path class="yzvsk8b0m"/></g><g filter="url(#icbTWvd)"><path class="m7cpxungq"/><path fill="url(#ioeE2Sb)" class="y-rsftqxe"/></g><g filter="url(#ihgU1Ib)"><path class="v_f_fqz2e"/><path fill="url(#iQlKIqe)" class="rc_fvefcz"/><path fill="url(#izQEpFd)" class="rc_fvefcz"/></g><g filter="url(#iPpD6Cd)"><path stroke="url(#iujvFOe)" class="i3v_ocbeg"/></g><g filter="url(#iSl9GBZ)"><path class="l-glfw9wr"/></g><g filter="url(#iOST2je)"><path fill="url(#iDd2w2c)" class="x_5dx7t4p"/></g><defs><radialGradient id="iVV4Xqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.52846 3.99287 -4.98791 -.66016 17.95 11.683)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="inK9nad" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 5.92 8.325)scale(3.04552 4.00157)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iJyrkyc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 4.592 8.295)scale(1.88495 1.44738)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="inDP7Fe" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 4.966 7.984)scale(2.16768 1.52694)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iIEazTd" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 5.55 13.741)scale(2.58712 3.59132)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="il0bmTb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 10.78 6.958)scale(1.78533 2.49497)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iAzOGYb" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.772 6.14)scale(1.68164 3.50692)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="idZqOsd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.46611 .61656 -.7854 -3.14146 24.262 11.741)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ivFzqMb" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.546 -4.69)scale(2.45256 1.93983)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="im7mQcF" cx="0" cy="0" r="1" gradientTransform="matrix(1.31714 .13816 -.22386 2.13415 12.835 8.715)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i7KN3ce" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 4.433 7.885)scale(2.55712 2.35718)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="iv3GZpc" cx="0" cy="0" r="1" gradientTransform="rotate(143.412 5.631 14.18)scale(5.96846 3.36558)" gradientUnits="userSpaceOnUse"><stop class="s2ayxoxhu"/><stop offset="1" class="j6izx0btu"/></radialGradient><radialGradient id="iv5mtxG" cx="0" cy="0" r="1" gradientTransform="rotate(117.506 5.304 14.348)scale(10.2174 6.6572)" gradientUnits="userSpaceOnUse"><stop class="c9qnqxb4v"/><stop offset="1" class="f6lyc94ec"/></radialGradient><radialGradient id="i0ILhtd" cx="0" cy="0" r="1" gradientTransform="rotate(133.238 6.282 9.661)scale(4.31097 4.07134)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="abn8efjgi"/><stop offset="1" class="v46c2zbrf"/></radialGradient><radialGradient id="iTOeiCe" cx="0" cy="0" r="1" gradientTransform="rotate(-144.77 15.756 10.469)scale(4.37936 1.86088)" gradientUnits="userSpaceOnUse"><stop class="jhjy8fbuk"/><stop offset="1" class="eb_-_cbgw"/></radialGradient><radialGradient id="icUTm6n" cx="0" cy="0" r="1" gradientTransform="rotate(-140.774 9.442 11.606)scale(.98834 .87647)" gradientUnits="userSpaceOnUse"><stop class="ui2onhbah"/><stop offset="1" class="r9xs6qbkj"/></radialGradient><radialGradient id="iUE5chd" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 .23438 -.1603 .3847 13.125 19.48)" gradientUnits="userSpaceOnUse"><stop class="i5_a4vbjv"/><stop offset="1" class="qromo9b3v"/></radialGradient><radialGradient id="i7V47Fd" cx="0" cy="0" r="1" gradientTransform="rotate(172.312 10.092 13.637)scale(15.1472 14.3188)" gradientUnits="userSpaceOnUse"><stop offset=".843" class="j4kd8gbkb"/><stop offset="1" class="wnvc0_kja"/></radialGradient><radialGradient id="ilsoP7B" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 5.59128 -12.27475 3.77323 12.104 24.364)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="zbp8lvp5i"/><stop offset="1" class="v5eaoeghz"/></radialGradient><radialGradient id="iue24wd" cx="0" cy="0" r="1" gradientTransform="matrix(2.17994 -.99088 1.20982 2.6616 21.752 9.878)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="i5JvI2d" cx="0" cy="0" r="1" gradientTransform="matrix(1.15236 .6459 -.1826 .32579 22.655 8.02)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="ib4B4rd" cx="0" cy="0" r="1" gradientTransform="matrix(1.32238 -.09837 .0769 1.03373 22.06 9.59)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="imPMIKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05694 0 0 -.8338 14.184 9.492)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iw1gDGe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69588 2.62656 -3.5156 -7.62384 20.718 9.022)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="ivZ9QDe" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 8.803 7.12)scale(1.97581 1.37592)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="ieVvjfb" cx="0" cy="0" r="1" gradientTransform="matrix(.94016 -3.04438 3.86274 1.19289 16.305 14.962)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iqGwKyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.70244 5.9555 -5.98739 -.7062 18.687 9.16)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iSkp4ud" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.75134 -5.78214 0 17.985 9.364)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="i9sRLWb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.04803 1.1869 -2.0435 -10.41288 19.8 10.538)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="ilu0X9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.00785 1.23691 0 20.23 8.656)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iMRYPnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14951 1.31741 0 16.395 8.455)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="ihQ2bId" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12566 0 0 -5.64508 22.677 9.958)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iUC6hsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60185 1.37883 -.92412 -1.0736 21.648 13.502)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iGIFwXG" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 13.698 -2.278)scale(1.83408 .56525)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iqSBRAe" cx="0" cy="0" r="1" gradientTransform="matrix(-.6826 0 0 -.19084 18.691 10.78)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iU01Hob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71056 -1.13022 0 20.125 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ixLJVab" cx="0" cy="0" r="1" gradientTransform="matrix(-.20311 -.26175 .36035 -.27963 19.925 9.043)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i94zjic" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71056 -1.13023 0 16.303 8.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iZO2N2L" cx="0" cy="0" r="1" gradientTransform="matrix(-.00677 -.4327 .52012 -.00814 16.052 9.162)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ioeE2Sb" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 12.17 -6.771)scale(2.6543 1.35788)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iQlKIqe" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 9.141 7.528)scale(4.26772 6.97748)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="izQEpFd" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 7.965 9.33)scale(1.21149 2.60645)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iVfn2yb" width="13.403" height="13.903" x="11.638" y="1.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/></filter><filter id="ibReF5d" width="15.898" height="17.05" x="7.69" y="13.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.345098 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.396078 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3480" result="effect2_innerShadow_4002_3480"/></filter><filter id="if9cLYb" width="15.258" height="14.494" x="7.176" y="15.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".25"/></filter><filter id="iY3Tqfc" width="14.977" height="12.277" x="7.209" y="17.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.12549 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/></filter><filter id="iKCTp2c" width="4.354" height="4.526" x="18.586" y="15.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.27451 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/></filter><filter id="iTDMaXb" width="3.759" height="5.328" x="19.417" y="15.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".5"/></filter><filter id="iXOShDd" width="1.206" height=".37" x="7.76" y="26.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".05"/></filter><filter id="iHn1T6d" width="1.261" height=".3" x="7.526" y="27.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".05"/></filter><filter id="iN6ASKc" width="1.206" height=".3" x="7.936" y="28.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".05"/></filter><filter id="iDJvnIc" width="2.969" height="2.818" x="12.701" y="8.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/></filter><filter id="i3UGF5c" width="2.818" height="3.068" x="21.033" y="7.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/></filter><filter id="iCJz6we" width="2.881" height="2.881" x="21.001" y="8.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".25"/></filter><filter id="iOBXqye" width="2.381" height="2.381" x="12.936" y="8.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".125"/></filter><filter id="ioJGHGA" width="8.925" height="9.776" x="13.752" y="5.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/></filter><filter id="iVIluFY" width="2.644" height="3.349" x="16.75" y="8.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".25"/></filter><filter id="i6ghJGX" width="2.144" height="2.849" x="17.142" y="8.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".125"/></filter><filter id="i41NUAe" width="3.292" height="1.386" x="16.568" y="11.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".05"/></filter><filter id="it1jZMd" width="2.653" height="1.126" x="19.014" y="8.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/></filter><filter id="itOqRvN" width="2.653" height="1.126" x="14.761" y="8.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/></filter><filter id="iV20zPe" width="2.173" height=".98" x="14.879" y="6.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/></filter><filter id="iGxlXhd" width="2.173" height=".98" x="19.623" y="6.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/></filter><filter id="islMrye" width=".714" height=".635" x="19.47" y="8.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".05"/></filter><filter id="i2WJeQe" width=".83" height=".85" x="20.193" y="8.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".1"/></filter><filter id="iR0P7Wd" width=".913" height=".961" x="16.302" y="8.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".1"/></filter><filter id="i0EkZMd" width=".824" height=".642" x="15.653" y="8.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".05"/></filter><filter id="iI3yxfd" width="2.255" height="1.131" x="19.513" y="6.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".1"/></filter><filter id="iEfSE8d" width="2.255" height="1.131" x="14.738" y="6.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".1"/></filter><filter id="icbTWvd" width="3.988" height="4.252" x="12.499" y="3.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/><feGaussianBlur result="effect2_foregroundBlur_4002_3480" stdDeviation=".25"/></filter><filter id="ihgU1Ib" width="7.747" height="5.126" x="15.4" y="2.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3480"/><feGaussianBlur result="effect2_foregroundBlur_4002_3480" stdDeviation=".125"/></filter><filter id="iPpD6Cd" width="1.077" height="2.097" x="15.382" y="3.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".1"/></filter><filter id="iSl9GBZ" width="5.815" height="3.14" x="17.611" y="4.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".375"/></filter><filter id="iOST2je" width="4.908" height="6.063" x="16.812" y="19.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3480" stdDeviation=".25"/></filter><linearGradient id="iMA5dRm" x1="22.325" x2="16.364" y1="3.403" y2="14.443" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="i6n3psd" x1="20.105" x2="12.386" y1="27.895" y2="19.395" gradientUnits="userSpaceOnUse"><stop class="pokolfbgc"/><stop offset="1" class="b3y8h4ksz"/></linearGradient><linearGradient id="ieoR1ac" x1="16.511" x2="16.511" y1="29.976" y2="27.265" gradientUnits="userSpaceOnUse"><stop class="ckcj4hbsb"/><stop offset="1" class="q93oiybtq"/></linearGradient><linearGradient id="i8WKeKc" x1="19.156" x2="11.437" y1="17.61" y2="26.11" gradientUnits="userSpaceOnUse"><stop class="tts0ot_3n"/><stop offset="1" class="luw3gnblf"/></linearGradient><linearGradient id="ijYBLRv" x1="21.839" x2="18.964" y1="18.208" y2="18.052" gradientUnits="userSpaceOnUse"><stop class="a_ut7cc2e"/><stop offset="1" class="cyj659bzg"/></linearGradient><linearGradient id="iw6XB4b" x1="21.308" x2="20.605" y1="16.458" y2="20.958" gradientUnits="userSpaceOnUse"><stop class="gla1f_2eg"/><stop offset="1" class="fx7b7_wnc"/></linearGradient><linearGradient id="iMrD4eb" x1="7.91" x2="9.065" y1="27.138" y2="27.208" gradientUnits="userSpaceOnUse"><stop class="igax9pb-n"/><stop offset="1" class="lys20yxtg"/></linearGradient><linearGradient id="iYRpZcd" x1="7.676" x2="8.905" y1="28.122" y2="28.128" gradientUnits="userSpaceOnUse"><stop class="igax9pb-n"/><stop offset="1" class="lys20yxtg"/></linearGradient><linearGradient id="iX7E2De" x1="8.086" x2="9.245" y1="29.036" y2="29.041" gradientUnits="userSpaceOnUse"><stop class="igax9pb-n"/><stop offset="1" class="lys20yxtg"/></linearGradient><linearGradient id="iZEsuVb" x1="11.922" x2="24.512" y1="13.706" y2="13.706" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="igEvI8q" x1="11.921" x2="24.512" y1="13.679" y2="13.679" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i3e5krc" x1="12.701" x2="15.293" y1="9.57" y2="9.57" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iDIobzc" x1="17.392" x2="18.214" y1="10.659" y2="10.659" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="i04J3Rb" x1="18.214" x2="18.214" y1="11.359" y2="10.825" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iShl9zb" x1="17.282" x2="17.686" y1="12.593" y2="11.969" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="i5VSctd" x1="20.806" x2="20.532" y1="9.017" y2="9.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipO19ck" x1="16.954" x2="16.68" y1="9.018" y2="9.187" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iujvFOe" x1="15.682" x2="16.159" y1="4.065" y2="5.18" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iDd2w2c" x1="20.437" x2="16.047" y1="20.172" y2="26.25" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="kfkqa5blx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pregnant-woman-dark" /></template>
<style>
.a_ut7cc2e {
  stop-color: var(--svg-color--8e6acb, #8E6ACB);
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a403usbll {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.214 12.043c-.456 0-.885-.11-1.245-.302c-.123-.064-.256.078-.178.192a1.692 1.692 0 0 0 2.846 0c.077-.119-.055-.256-.178-.192c-.36.192-.784.302-1.245.302Z");
}

.abn8efjgi {
  stop-color: var(--svg-color--513091, #513091);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.ajxjvpbbc {
  d: path("M20.127 8.552a.782.782 0 0 1 .753.987h-1.51a.785.785 0 0 1 .757-.988");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b_1v1rb3o {
  d: path("M20.694 17.177a36 36 0 0 1-.277 2.61h1.5c.148-.873.224-1.863.258-2.581a.72.72 0 0 0-.726-.748a.764.764 0 0 0-.755.72");
}

.b3y8h4ksz {
  stop-color: var(--svg-color--7657b1, #7657B1);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.c9qnqxb4v {
  stop-color: var(--svg-color--9c7cd3, #9C7CD3);
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckcj4hbsb {
  stop-color: var(--svg-color--5d4097, #5D4097);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co4ddab0u {
  cx: 16.065px;
  cy: 8.886px;
  rx: 0.341px;
  ry: 0.173px;
}

.cp_ktim0y {
  d: path("M18.525 13.68c.219.008.447.026.674.043c-.227-.017-.446-.035-.674-.043");
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyj659bzg {
  stop-color: var(--svg-color--7555ae, #7555AE);
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d5nkjk5vc {
  d: path("M17.015 9.242c0-.252-.205-.42-.26-.471l-.253.244l.155.316z");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dta2yqblg {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.913 7.415c.282-.069.985-.034 1.454.302");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e09eu8bna {
  d: path("M14.127 10.433a.94.94 0 1 0 0-1.881a.94.94 0 0 0 0 1.881");
}

.eb_-_cbgw {
  stop-color: var(--svg-color--6f56b0, #6F56B0);
  stop-opacity: 0;
}

.esboituev {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m17.88 9.177l-.466 1.489a.472.472 0 0 0 .456.612h.688c.323 0 .551-.31.456-.612l-.465-1.489c-.1-.33-.565-.33-.67 0");
}

.f4sgag53f {
  d: path("M22.442 10.903a1.41 1.41 0 1 0 0-2.82a1.41 1.41 0 0 0 0 2.82");
}

.f6lyc94ec {
  stop-color: var(--svg-color--8563c2, #8563C2);
  stop-opacity: 0;
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.fx7b7_wnc {
  stop-color: var(--svg-color--a281e0, #A281E0);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gi5elwbsw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.07 8.717c.055.074-.061.165-.194.264c-.132.1-.23.169-.286.094c-.056-.074.006-.215.139-.314c.132-.099.285-.119.34-.044");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.gla1f_2eg {
  stop-color: var(--svg-color--a281e0, #A281E0);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gsrv7ubtl {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M22.442 10.433a.94.94 0 1 0 0-1.881a.94.94 0 0 0 0 1.881");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.haf370ocm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.91 27.138c.174.013.6.045.906.07");
}

.hefkts3ys {
  d: path("M20.823 9.23a.74.74 0 0 0-.203-.405l-.227.25l.102.2z");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i_ru-mbhh {
  d: path("M20.07 8.717c.055.074-.061.165-.194.264c-.132.1-.23.169-.286.094c-.056-.074.006-.215.139-.314c.132-.099.285-.119.34-.044");
}

.i3v_ocbeg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.682 3.764c.02.213.205 1.013.477 1.497");
}

.i5_a4vbjv {
  stop-color: var(--svg-color--725e92, #725E92);
}

.ibiyjmt2x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.676 28.122h.96");
}

.igax9pb-n {
  stop-color: var(--svg-color--34211f, #34211F);
}

.j1bn99p7h {
  fill: var(--svg-color--000, #000);
  d: path("M16.749 9.333a.446.446 0 0 0-.448-.447a.446.446 0 0 0-.398.653h.792a.44.44 0 0 0 .054-.206");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j4kd8gbkb {
  stop-color: var(--svg-color--432f2d, #432F2D);
  stop-opacity: 0;
}

.j6izx0btu {
  stop-color: var(--svg-color--755fa5, #755FA5);
  stop-opacity: 0;
}

.jhjy8fbuk {
  stop-color: var(--svg-color--7a63b9, #7A63B9);
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jloy9jwlq {
  d: path("M13.479 16.192c.687-.875 2.474-2.375 3.28-3.015h3.267c2.15.587 2.562 2.625 2.562 3.625V28.13c0 1.562-1.208 1.88-1.812 1.844h-9.891c-2.281 0-4.093-3.188-2.719-6.61c1.264-2.63 3.502-3.447 4.787-3.74a.16.16 0 0 0 .093-.243c-.98-1.43-.39-2.141.433-3.189");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kfkqa5blx {
  stop-color: var(--svg-color--675454, #675454);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kuk58bcae {
  d: path("M16.301 8.552a.782.782 0 0 0-.753.987h1.51a.787.787 0 0 0-.757-.988");
}

.l-glfw9wr {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m20.322 5.831l-1.249.23a.603.603 0 1 1-.11-1.196h2.05c1.213 0 1.615 1.222 1.664 1.64a2.76 2.76 0 0 0-2.355-.674");
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lg5pgtyig {
  fill: var(--svg-color--272528, #272528);
  d: path("M17.214 8.994c-.232-.408-.586-.731-1.346-.731c-.334 0-.655.092-.94.323c-.236.19-.204.433-.022.524l.487.278c.571-.184 1.203-.209 1.821-.394");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lh8aekx1o {
  fill-rule: evenodd;
  d: path("M24.507 10.727a2.84 2.84 0 0 0 .284-1.25a2.9 2.9 0 0 0-.236-1.143h.005a3 3 0 0 0-.246-.45l-.002-.002a2.84 2.84 0 0 1-.46-1.551v-.009a2.89 2.89 0 0 0-2.89-2.89c-.16 0-.31-.07-.4-.203a2.9 2.9 0 0 0-2.348-1.206c-.966 0-1.826.479-2.349 1.206a.5.5 0 0 1-.399.204h-.074a2.89 2.89 0 0 0-2.815 2.89v.008c0 .55-.16 1.09-.46 1.551l-.003.003a2.89 2.89 0 0 0-.193 2.842a.45.45 0 0 1 0 .399a2.814 2.814 0 0 0 2.535 4.05h7.516a2.814 2.814 0 0 0 2.535-4.05a.45.45 0 0 1 0-.399m-10.738-2.34h-.01l1.05 2.063c.107 2.454 1.065 0 3.405 0s3.36 2.732 3.468.277l.995-2.8c-.047-1.09-.837-1.167-.995-1.167h-2.82a3.38 3.38 0 0 1-2.793-1.465a.23.23 0 0 0-.404.044l-.072.17a2.02 2.02 0 0 1-1.132 1.117c-.207.107-.692.43-.71 1.26l.01.268z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.luw3gnblf {
  stop-color: var(--svg-color--584487, #584487);
}

.lys20yxtg {
  stop-color: var(--svg-color--34211f, #34211F);
  stop-opacity: 0;
}

.m539_vbau {
  d: path("M22.442 10.433a.94.94 0 1 0 0-1.881a.94.94 0 0 0 0 1.881");
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.m6pycabqr {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m15.238 7.936l-.003.002a.235.235 0 0 1-.242-.403h.001l.003-.002l.008-.005a2 2 0 0 1 .13-.067c.087-.041.21-.094.36-.142a2.46 2.46 0 0 1 1.163-.095a.235.235 0 0 1-.082.462c-.35-.061-.684 0-.939.08a2.4 2.4 0 0 0-.399.17");
}

.m7cpxungq {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M13.775 4.248c.495-.524 1.432-.525 1.866-.447l.346 1.13c-.221-.034-.418.044-.585.206c-.392 1.104-1.742 1.713-2.368 1.879c-.13-1.307.096-2.085.74-2.768");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbv_48bws {
  fill: var(--svg-color--000, #000);
  d: path("M19.68 9.333c0-.248.198-.447.447-.447a.446.446 0 0 1 .398.653h-.792a.4.4 0 0 1-.054-.206");
}

.mezfmvbmf {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M18.214 12.043c-.456 0-.885-.11-1.245-.302c-.123-.064-.256.078-.178.192a1.692 1.692 0 0 0 2.846 0c.077-.119-.055-.256-.178-.192c-.36.192-.784.302-1.245.302");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n4l00c1xr {
  d: path("M13.759 8.387h.01l-.009-.232l-.008-.269c.017-.83.502-1.152.709-1.26q.022-.006.045-.017l.045-.018c.467-.215.844-.59 1.042-1.081l.072-.17a.23.23 0 0 1 .404-.045a3.38 3.38 0 0 0 2.793 1.466h2.82c.158 0 .948.076.995 1.166l-.104 2.692c-.108 2.454-2.025 4.102-4.365 4.102s-4.256-1.648-4.364-4.102z");
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
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

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pokolfbgc {
  stop-color: var(--svg-color--7a61b9, #7A61B9);
}

.pq6t-dhpn {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.308 8.314c.572 0 1.055.395 1.187.928a.24.24 0 0 1-.235.298h-1.954a.202.202 0 0 1-.199-.238c.11-.561.604-.988 1.201-.988");
}

.q0ib_xk4x {
  d: path("M20.33 16.174c-.568-.03-1.704.276-1.704 1.75c0 .752-.283 1.867-.424 2.33h.058c-.526 1.723-2.32 4.874-6.386 5.905c-.765.138-1.032-.064-1.428-.525a27 27 0 0 0-.348-.396a.52.52 0 0 0-.748-.025a.52.52 0 0 0-.048.7c.093.116.187.228.256.3a5.6 5.6 0 0 1-1.01-.1c-.534-.11-.697.249-.718.373c-.027.153 1.515.324 1.76.416c-.202-.009-.569.046-.604.447a.455.455 0 0 0 .364.516c-.07.054-1.742.317-1.672.57c.1.363.423.382.543.382a.43.43 0 0 0-.171.434c.051.309.397.409.595.409h.048c.52.015 4.622.127 8.21-2.359c2.773-2.146 4.071-4.421 4.698-7.019l-.288-.027h.288a9.8 9.8 0 0 0 .331-2.23c.046-1.308-.847-1.851-1.602-1.851");
}

.q93oiybtq {
  stop-color: var(--svg-color--5d4097, #5D4097);
  stop-opacity: 0;
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qromo9b3v {
  stop-color: var(--svg-color--725e92, #725E92);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r9xs6qbkj {
  stop-color: var(--svg-color--423363, #423363);
  stop-opacity: 0;
}

.rc_fvefcz {
  d: path("M17.686 2.67c-.992-.219-1.883.77-1.986 1.138c.921 3.104 3.252 2.934 5.553 2.679c1.377-.153 1.526.474 1.644.778c0-3.445-2.929-4.091-5.186-4.59z");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.s2ayxoxhu {
  stop-color: var(--svg-color--755fa5, #755FA5);
}

.s5d7bhbfb {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M19.214 8.994c.233-.408.586-.731 1.347-.731c.333 0 .654.092.94.323c.235.19.203.433.02.524l-.486.278c-.571-.184-1.202-.209-1.82-.394");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.smds5mbqf {
  d: path("M19.035 17.517c0-1.562 1.204-1.887 1.806-1.855c.8 0 1.746.576 1.698 1.962a10.4 10.4 0 0 1-.352 2.362h-3.6c.149-.492.448-1.673.448-2.47");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t3qqjcb3f {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.12 8.314c-.572 0-1.055.395-1.187.928a.24.24 0 0 0 .235.298h1.954a.202.202 0 0 0 .199-.238a1.23 1.23 0 0 0-1.201-.988");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.trugahbpj {
  fill: var(--svg-color--462e2c, #462E2C);
  d: path("M11.882 26.24c4.56-1.155 6.421-4.827 6.85-6.557l2.703-2.005l.752 2.307c-.664 2.752-2.04 5.192-4.977 7.466c-3.972 2.752-8.539 2.498-8.749 2.498s-.576-.105-.63-.433a.45.45 0 0 1 .181-.46c-.127 0-.47-.02-.575-.405a.49.49 0 0 1 .16-.512a.48.48 0 0 1-.385-.547c.037-.425.426-.483.64-.473c-.26-.098-.282-.37-.254-.532c.022-.132.195-.512.76-.395a6 6 0 0 0 1.07.106a6 6 0 0 1-.27-.317a.55.55 0 0 1 .05-.742a.55.55 0 0 1 .793.025c.112.126.24.27.368.42c.42.488.703.703 1.513.557");
}

.tts0ot_3n {
  stop-color: var(--svg-color--553697, #553697);
}

.ui2onhbah {
  stop-color: var(--svg-color--423363, #423363);
}

.v_f_fqz2e {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M17.686 2.67c-.992-.219-1.883.77-1.986 1.138c.921 3.104 3.252 2.934 5.553 2.679c1.377-.153 1.526.474 1.644.778c0-3.445-2.929-4.091-5.186-4.59z");
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v46c2zbrf {
  stop-color: var(--svg-color--785cad, #785CAD);
  stop-opacity: 0;
}

.v5eaoeghz {
  stop-color: var(--svg-color--3e2232, #3E2232);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wc4eq0bch {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m21.482 7.535l-.12.202za.235.235 0 0 1-.241.404l-.004-.003l-.02-.01l-.08-.04a2.4 2.4 0 0 0-.3-.12a2 2 0 0 0-.938-.08a.235.235 0 1 1-.082-.462c.45-.08.866 0 1.164.095a3 3 0 0 1 .489.21l.008.004z");
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wn-fsabnt {
  cx: 16.065px;
  cy: 8.886px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.341px;
  ry: 0.173px;
}

.wnvc0_kja {
  stop-color: var(--svg-color--432f2d, #432F2D);
}

.x_5dx7t4p {
  d: path("M20.345 20.172c-.462 2.15-2.257 4.286-3.033 5.062c2.638-1.775 3.747-4.13 3.908-5.062z");
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xs7bh_47t {
  d: path("M11.882 26.24c4.56-1.155 6.421-4.827 6.85-6.557l3.454.302c-.663 2.752-2.038 5.192-4.976 7.466c-3.972 2.752-8.539 2.498-8.749 2.498s-.576-.105-.63-.433a.45.45 0 0 1 .181-.46c-.127 0-.47-.02-.575-.405a.49.49 0 0 1 .16-.512a.48.48 0 0 1-.385-.547c.037-.425.426-.483.64-.473c-.26-.098-.282-.37-.254-.532c.022-.132.195-.512.76-.395a6 6 0 0 0 1.07.106a6 6 0 0 1-.27-.317a.55.55 0 0 1 .05-.742a.55.55 0 0 1 .793.026c.112.125.24.27.368.42c.42.487.703.702 1.513.556");
}

.xuhwwnbiu {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M14.127 10.433a.94.94 0 1 0 0-1.881a.94.94 0 0 0 0 1.881");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xvhp6rcuw {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m17.87 9.298l-.599 1.489a.472.472 0 0 0 .456.612h.69c.322 0 .55-.31.455-.612l-.465-1.489c-.1-.33-.432-.33-.537 0");
}

.xx4jetbse {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M8.086 29.036h.906");
}

.y-rsftqxe {
  d: path("M13.775 4.248c.495-.524 1.432-.525 1.866-.447l.346 1.13c-.221-.034-.418.044-.585.206c-.392 1.104-1.742 1.713-2.368 1.879c-.13-1.307.096-2.085.74-2.768");
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yusrdebwv {
  d: path("m17.88 9.177l-.466 1.489a.472.472 0 0 0 .456.612h.688c.323 0 .551-.31.456-.612l-.465-1.489c-.1-.33-.565-.33-.67 0");
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.yzvsk8b0m {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.593 7.415c-.283-.069-.985-.034-1.455.302");
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zbp8lvp5i {
  stop-color: var(--svg-color--3e2232, #3E2232);
  stop-opacity: 0;
}

.zi5e98b5e {
  d: path("M14.11 10.903a1.41 1.41 0 1 0 0-2.819a1.41 1.41 0 0 0 0 2.819");
}

.zt2nfysbf {
  d: path("M18.236 13.68H18.2c.087 0 .166 0 .254.008c-.07-.008-.15-.008-.22-.008");
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
