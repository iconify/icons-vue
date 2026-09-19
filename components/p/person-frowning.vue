<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irvRVIc)" class="r-p1r0bka"/><path fill="url(#imKNpjb)" class="r-p1r0bka"/><path fill="url(#iDMBn4d)" class="r-p1r0bka"/><path class="q3j5p4bnu"/><path fill="url(#iDYTGHc)" class="ki9ou8znj"/><path fill="url(#i7W7S8b)" class="syihbl_wg"/><path fill="url(#ih1c9Td)" class="syihbl_wg"/><path fill="url(#iWHphyd)" class="vs2_45bjo"/><path fill="url(#iefNlFd)" class="vs2_45bjo"/><g filter="url(#i0CGOIe)"><path fill="url(#i8nTmac)" class="e7xledbyg"/></g><path fill="url(#ilOVuEb)" class="e7xledbyg"/><path fill="url(#iAlXAxb)" class="e7xledbyg"/><path fill="url(#ifuQxsc)" class="e7xledbyg"/><path fill="url(#i9ypMqZ)" class="e7xledbyg"/><g filter="url(#iWwi3Ce)"><path class="rvl8oblni"/></g><g filter="url(#ik5uThe)"><path fill="url(#iCALrpe)" class="i9z5qtbjx"/><path fill="url(#imgWJbd)" class="i9z5qtbjx"/><path fill="url(#iWaM1ee)" class="i9z5qtbjx"/><path fill="url(#ihilOpb)" class="i9z5qtbjx"/></g><path class="lh0sls_ft"/><g filter="url(#iGVfb7P)"><path fill="url(#iABmmic)" class="cylezxb0d"/><path fill="url(#iEsx8gb)" class="cylezxb0d"/><path fill="url(#ib18DOT)" class="cylezxb0d"/><path fill="url(#iR44HSb)" class="cylezxb0d"/><path fill="url(#iRrerud)" class="cylezxb0d"/></g><g filter="url(#iaM5qBe)"><path fill="url(#ieh9RIc)" class="lvz3e3h4f"/><path fill="url(#iFFOg6d)" class="lvz3e3h4f"/></g><g filter="url(#ieyBqMb)"><path fill="url(#iAUfbpe)" class="wxpwi-bdn"/><path fill="url(#iVR1jqc)" class="wxpwi-bdn"/><path fill="url(#ihlg1Pb)" class="wxpwi-bdn"/><path fill="url(#iCa7YRb)" class="wxpwi-bdn"/><path fill="url(#iFWCOCc)" class="wxpwi-bdn"/></g><path class="sm0-17bla"/><path fill="url(#ihX9TAe)" class="b29w4ybxt"/><path class="oepsspbmg"/><g filter="url(#i2dASsd)"><path class="hl3rkgbkc"/><path fill="url(#ikHBfxd)" class="tvcqtubby"/></g><g filter="url(#iw34F5c)"><path fill="url(#i3HEzRb)" class="k_6yzcblu"/></g><path class="e1xhgwnaj"/><path fill="url(#i9HFGwc)" class="z_13pt5jn"/><path class="iimn87bbj"/><g filter="url(#ir2w4tA)"><path fill="url(#iymFYKe)" class="bq0qwccbl"/></g><g filter="url(#ikh0uub)"><ellipse transform="rotate(-27.914 12.798 12.252)" class="u0zy11lmg"/><ellipse fill="url(#iC7J7Fe)" transform="rotate(-27.914 12.798 12.252)" class="o4mllpb5q"/></g><path fill="url(#iPbfBMb)" class="p7vsprbwu"/><path fill="url(#iK95JZb)" class="p7vsprbwu"/><path fill="url(#iC0t1SY)" class="p7vsprbwu"/><path fill="url(#i2bVPyb)" class="p2uhow_xp"/><path fill="url(#ib81y7Q)" class="p2uhow_xp"/><g filter="url(#ikPP6re)"><path class="rnkq2bboc"/></g><g filter="url(#i0EGsfb)"><path class="sp-431b1q"/></g><g filter="url(#iAqVkcc)"><path class="y9go09bul"/></g><g filter="url(#iQap2Pe)"><path class="j5a_ccbih"/></g><g filter="url(#iN5A6gb)"><path stroke="url(#i9TdWXc)" class="ohv43gbwb"/></g><g filter="url(#iqjjt5d)"><path stroke="url(#iSTprKc)" class="hgp_qqb3o"/></g><defs><radialGradient id="irvRVIc" cx="0" cy="0" r="1" gradientTransform="matrix(8.51391 12.88852 -13.10788 8.65882 12.22 20)" gradientUnits="userSpaceOnUse"><stop class="pbeg7ubou"/><stop offset="1" class="r5dp7ehbg"/></radialGradient><radialGradient id="imKNpjb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.88287 3.79 -6.9237 -12.57388 23.777 25)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="nhsctebvu"/><stop offset="1" class="antt9347k"/></radialGradient><radialGradient id="iDYTGHc" cx="0" cy="0" r="1" gradientTransform="matrix(1.53251 3.15635 -5.19177 2.52078 14.774 21.344)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="jjimsbcbk"/><stop offset="1" class="tkrwpobdo"/></radialGradient><radialGradient id="i7W7S8b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00887 4.14514 -4.92411 -1.19846 23.268 14.808)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="xitcw8bap"/><stop offset="1" class="v2o3hnbel"/></radialGradient><radialGradient id="ih1c9Td" cx="0" cy="0" r="1" gradientTransform="matrix(.38381 .52637 -.44716 .32605 22.292 15.16)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iWHphyd" cx="0" cy="0" r="1" gradientTransform="rotate(64.592 -7.461 14.401)scale(3.88488 1.76585)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="iefNlFd" cx="0" cy="0" r="1" gradientTransform="matrix(.4167 1.30495 -1.14471 .36554 9.615 14.95)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="i8nTmac" cx="0" cy="0" r="1" gradientTransform="matrix(-6.84059 0 0 -12.1009 19.682 13.577)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iAlXAxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 17.0547 -14.1233 0 16.582 5.746)" gradientUnits="userSpaceOnUse"><stop offset=".751" class="jfo6z-bud"/><stop offset=".952" class="g7vim1bgz"/></radialGradient><radialGradient id="ifuQxsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.75456 2.17127 0 19.21 12.11)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="qtwfj5bch"/><stop offset="1" class="wtzd4lbuc"/></radialGradient><radialGradient id="i9ypMqZ" cx="0" cy="0" r="1" gradientTransform="rotate(-90.716 12.558 -.31)scale(1.7547 1.90952)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="yq9cl_lgn"/><stop offset="1" class="sw1t1obly"/></radialGradient><radialGradient id="iEsx8gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75329 8.42189 0 9.165 11.507)" gradientUnits="userSpaceOnUse"><stop class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="ib18DOT" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75329 8.42189 0 22.369 11.507)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iR44HSb" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 10.994 -.323)scale(4.55383 2.42522)" gradientUnits="userSpaceOnUse"><stop class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iRrerud" cx="0" cy="0" r="1" gradientTransform="matrix(1.18434 1.93001 -4.469 2.74236 14.824 1.211)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="ieh9RIc" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.9 2.978)scale(5.29564 1.4739)" gradientUnits="userSpaceOnUse"><stop class="b6ai19bel"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iFFOg6d" cx="0" cy="0" r="1" gradientTransform="matrix(4.21094 -6.66733 7.38672 4.66529 8.902 9.325)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iAUfbpe" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -9.412 91.227)scale(4.5525 1.74584)" gradientUnits="userSpaceOnUse"><stop class="da8sh5f1a"/><stop offset="1" class="lguy1wbep"/></radialGradient><radialGradient id="iVR1jqc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.81142 -4.84625 2.70272 -1.56791 22.72 10.641)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="ihlg1Pb" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 13.871 -1.112)scale(3.35119 2.40031)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iCa7YRb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.2787 1.50634 -1.6284 -6.7875 22.28 4.463)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="iFWCOCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.15353 .5021 -2.29559 -.70192 20.526 4.3)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="ihX9TAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.0616 -1.6886 0 18.863 12.378)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ikHBfxd" cx="0" cy="0" r="1" gradientTransform="matrix(-.30346 -.39106 .53838 -.4178 18.564 12.488)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9HFGwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.06166 -1.68868 0 13.153 12.378)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iC7J7Fe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.623 .042)scale(.64658 .77722)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iK95JZb" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 2.852 20.737)scale(3.04835 2.90836)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iC0t1SY" cx="0" cy="0" r="1" gradientTransform="matrix(1.0308 -1.41461 1.18572 .86402 22.522 13.108)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="ib81y7Q" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -.616 10.05)scale(2.76965 2.72282)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="i0CGOIe" width="14.123" height="16.349" x="9.383" y="5.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_192"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_1800_192" result="effect2_innerShadow_1800_192"/></filter><filter id="iWwi3Ce" width="4.456" height="5.795" x="13.509" y="11.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".5"/></filter><filter id="ik5uThe" width="2.656" height="3.995" x="14.68" y="12.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".05"/></filter><filter id="iGVfb7P" width="16.844" height="10.78" x="7.586" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_192"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_1800_192" result="effect2_innerShadow_1800_192"/></filter><filter id="iaM5qBe" width="8.961" height="8.186" x="7.879" y="2.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".25"/></filter><filter id="ieyBqMb" width="8.743" height="7.929" x="15.554" y="3.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".25"/></filter><filter id="i2dASsd" width=".968" height=".849" x="17.934" y="11.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".05"/></filter><filter id="iw34F5c" width="1.043" height="1.072" x="19.064" y="11.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".1"/></filter><filter id="ir2w4tA" width="1.167" height="1.238" x="13.25" y="11.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".1"/></filter><filter id="ikh0uub" width="1.133" height=".86" x="12.232" y="11.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".05"/></filter><filter id="ikPP6re" width="1.585" height="2.959" x="8.192" y="11.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".125"/></filter><filter id="i0EGsfb" width="1.739" height="2.991" x="22.251" y="11.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".125"/></filter><filter id="iAqVkcc" width="2.939" height="1.538" x="17.966" y="9.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.262745 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_192"/></filter><filter id="iQap2Pe" width="2.939" height="1.538" x="11.468" y="9.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.262745 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_192"/></filter><filter id="iN5A6gb" width="2.789" height="1.388" x="17.991" y="9.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".1"/></filter><filter id="iqjjt5d" width="2.789" height="1.388" x="11.493" y="9.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_192" stdDeviation=".1"/></filter><linearGradient id="iDMBn4d" x1="16.591" x2="16.591" y1="30.241" y2="29.549" gradientUnits="userSpaceOnUse"><stop class="nq482mihq"/><stop offset="1" class="xn3x1ebqw"/></linearGradient><linearGradient id="ilOVuEb" x1="22.756" x2="17.061" y1="15.782" y2="15.782" gradientUnits="userSpaceOnUse"><stop class="aflrgacjk"/><stop offset="1" class="pp1jb50uj"/></linearGradient><linearGradient id="iCALrpe" x1="16.008" x2="17.127" y1="14.661" y2="14.661" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="imgWJbd" x1="14.605" x2="16.01" y1="14.457" y2="14.535" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iWaM1ee" x1="16.008" x2="16.008" y1="15.183" y2="16.297" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="ihilOpb" x1="16.008" x2="16.008" y1="12.242" y2="12.791" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iABmmic" x1="23.026" x2="9.78" y1="6.167" y2="6.167" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="i3HEzRb" x1="19.881" x2="19.471" y1="12.448" y2="12.701" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iymFYKe" x1="14.127" x2="13.716" y1="12.448" y2="12.701" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPbfBMb" x1="24.43" x2="22.851" y1="12.483" y2="15.331" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="i2bVPyb" x1="8.354" x2="10.262" y1="13.405" y2="13.238" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="i9TdWXc" x1="20.222" x2="18.066" y1="10.425" y2="9.391" gradientUnits="userSpaceOnUse"><stop class="z_rhz9mhr"/><stop offset="1" class="m2-bjqbim"/></linearGradient><linearGradient id="iSTprKc" x1="12.051" x2="14.207" y1="10.425" y2="9.391" gradientUnits="userSpaceOnUse"><stop class="z_rhz9mhr"/><stop offset="1" class="m2-bjqbim"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-frowning" /></template>
<style>
.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.aflrgacjk {
  stop-color: var(--svg-color--ffd93b, #FFD93B);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.antt9347k {
  stop-color: var(--svg-color--ff7f41, #FF7F41);
  stop-opacity: 0;
}

.b29w4ybxt {
  d: path("M18.866 11.754a1.168 1.168 0 0 1 1.125 1.475h-2.256a1.172 1.172 0 0 1 1.13-1.476");
}

.b6ai19bel {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bq0qwccbl {
  d: path("M14.218 12.784c0-.377-.307-.629-.39-.705l-.378.365l.232.473z");
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
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

.cylezxb0d {
  d: path("M22.36 4.885a3.04 3.04 0 0 1 1.66 1.375a3.1 3.1 0 0 1-.14 3.306a2.04 2.04 0 0 0-.353 1.144v1.554a2.3 2.3 0 0 0-.873-.35l.102-2.103a1.897 1.897 0 0 0-1.804-1.874H19.12a3.17 3.17 0 0 1-2.894-1.887a.87.87 0 0 0-.805-.548h-1.666c-2.415 0-4.372 1.98-4.372 4.422l.04 2.011c-.332.049-.68.16-.942.345v-1.57a2.04 2.04 0 0 0-.354-1.144a3.13 3.13 0 0 1-.187-3.2a3.06 3.06 0 0 1 1.7-1.474a3.5 3.5 0 0 0 1.811-1.453A3.04 3.04 0 0 1 14.033 2c.423 0 .826.091 1.2.246a1.95 1.95 0 0 0 1.562 0c.368-.155.77-.246 1.194-.246c1.103 0 2.068.597 2.602 1.48a3.3 3.3 0 0 0 1.77 1.405");
}

.da8sh5f1a {
  stop-color: var(--svg-color--ffe137, #FFE137);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e1xhgwnaj {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.88 11.398c-.855 0-1.577.589-1.773 1.385a.36.36 0 0 0 .35.446h2.92c.185 0 .334-.17.297-.355a1.83 1.83 0 0 0-1.794-1.476");
}

.e7xledbyg {
  d: path("M9.695 17.195a5.124 5.124 0 0 0 5.084 4.456h2.469a5.124 5.124 0 0 0 5.084-4.456c.155-2.465.31-4.92.424-7.384a1.897 1.897 0 0 0-1.804-1.874H19.12a3.17 3.17 0 0 1-2.894-1.888a.87.87 0 0 0-.805-.547h-1.666c-2.415 0-4.372 1.98-4.372 4.422c0 2.434.152 4.83.312 7.27");
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.ft5dv1b6b {
  fill: none;
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g7vim1bgz {
  stop-color: var(--svg-color--ed7b14, #ED7B14);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.hgp_qqb3o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.982 9.637c-.304.327-1.077.855-2.189.78");
}

.hl3rkgbkc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.78 12c.083.112-.09.247-.288.395s-.345.252-.428.14c-.083-.11.01-.32.207-.468c.198-.148.426-.178.51-.067");
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.i9z5qtbjx {
  d: path("m15.508 12.642l-.695 2.405c-.142.495.198.99.68.99h1.03c.482 0 .823-.503.68-.99l-.694-2.405c-.15-.533-.845-.533-1.001 0");
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.iimn87bbj {
  fill: var(--svg-color--000, #000);
  d: path("M13.82 12.921a.666.666 0 0 0-.67-.669a.666.666 0 0 0-.594.977h1.184a.66.66 0 0 0 .08-.308");
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.j5a_ccbih {
  stroke: var(--svg-color--c25938, #C25938);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M13.982 9.7c-.304.326-1.077.854-2.189.78");
}

.jfo6z-bud {
  stop-color: var(--svg-color--fca33b, #FCA33B);
  stop-opacity: 0;
}

.jjimsbcbk {
  stop-color: var(--svg-color--e17b01, #E17B01);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.k_6yzcblu {
  d: path("M19.906 12.768a1.1 1.1 0 0 0-.302-.606l-.34.373l.153.299z");
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.ki9ou8znj {
  d: path("M16.019 24.5c-1.382 0-2.5-1.194-2.5-2.671V18.67c0-1.477 1.117-2.671 2.5-2.671s2.5 1.194 2.5 2.671v3.158c0 1.477-1.117 2.671-2.5 2.671");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lguy1wbep {
  stop-color: var(--svg-color--ffe137, #FFE137);
  stop-opacity: 0;
}

.lh0sls_ft {
  stroke: var(--svg-color--990838, #990838);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M14.672 17.584c.764-.525 1.875-.525 2.645 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.lvz3e3h4f {
  d: path("M16.312 6.229a3 3 0 0 1-.086-.18a.87.87 0 0 0-.805-.547h-1.666c-2.415 0-4.372 1.98-4.372 4.422v.36C8.938 9.945 8.38 9.23 8.38 8.075c0-1.402 1.023-2.111 1.675-2.563c.184-.128.339-.235.433-.332q.06-.061.13-.137c.457-.485 1.272-1.35 2.695-1.727c.8-.213 1.614-.24 2.223-.206c.473.027.805.435.805.908V6.21z");
}

.m2-bjqbim {
  stop-color: var(--svg-color--c76f5a, #C76F5A);
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

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nhsctebvu {
  stop-color: var(--svg-color--ff7f41, #FF7F41);
}

.nq482mihq {
  stop-color: var(--svg-color--ff4b25, #FF4B25);
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o4mllpb5q {
  cx: 12.798px;
  cy: 12.252px;
  rx: 0.51px;
  ry: 0.258px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oepsspbmg {
  fill: var(--svg-color--000, #000);
  d: path("M18.197 12.921c0-.371.298-.668.67-.668a.666.666 0 0 1 .594.976h-1.184a.6.6 0 0 1-.08-.308");
}

.ohv43gbwb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.291 9.637c.304.327 1.078.855 2.19.78");
}

.p2uhow_xp {
  d: path("M9.395 11.145a2.106 2.106 0 0 0 .181 4.187a102 102 0 0 1-.18-4.187");
}

.p7vsprbwu {
  d: path("M22.449 15.331q.131-2.087.241-4.176a2.106 2.106 0 0 1-.242 4.176");
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pbeg7ubou {
  stop-color: var(--svg-color--e3481b, #E3481B);
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp1jb50uj {
  stop-color: var(--svg-color--ffd93b, #FFD93B);
  stop-opacity: 0;
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q3j5p4bnu {
  fill: var(--svg-color--ffd342, #FFD342);
  d: path("M16.019 24.5c-1.382 0-2.5-1.194-2.5-2.671V18.67c0-1.477 1.117-2.671 2.5-2.671s2.5 1.194 2.5 2.671v3.158c0 1.477-1.117 2.671-2.5 2.671");
}

.qtwfj5bch {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-p1r0bka {
  d: path("M26.019 30v-.384c0-5.305-4.474-9.616-10-9.616c-5.525.01-10 4.311-10 9.616V30z");
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r5dp7ehbg {
  stop-color: var(--svg-color--ff7425, #FF7425);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rnkq2bboc {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M9.417 12.01a1.25 1.25 0 0 0 .11 2.459q-.07-1.23-.11-2.46");
}

.rvl8oblni {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.372 12.898l-.83 2.405c-.143.495.198.99.68.99h1.03c.482 0 .823-.503.68-.99l-.695-2.405c-.149-.533-.709-.533-.865 0");
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.sm0-17bla {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.137 11.398c.854 0 1.576.59 1.773 1.385a.36.36 0 0 1-.35.446h-2.92a.3.3 0 0 1-.297-.355a1.83 1.83 0 0 1 1.794-1.476");
}

.sp-431b1q {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M22.5 14.48q.077-1.245.145-2.491a1.25 1.25 0 0 1-.144 2.49");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.sw1t1obly {
  stop-color: var(--svg-color--ef9330, #EF9330);
  stop-opacity: 0;
}

.syihbl_wg {
  d: path("M22.37 15.212a2.14 2.14 0 0 0 1.183-.404v1.218a2.84 2.84 0 0 1-1.755 2.642q.336-.713.453-1.544z");
}

.tkrwpobdo {
  stop-color: var(--svg-color--e17b01, #E17B01);
  stop-opacity: 0;
}

.tvcqtubby {
  d: path("M18.78 12c.083.112-.09.247-.288.395s-.345.252-.428.14c-.083-.11.01-.32.207-.468c.198-.148.426-.178.51-.067");
}

.u0zy11lmg {
  cx: 12.798px;
  cy: 12.252px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.51px;
  ry: 0.258px;
}

.v2o3hnbel {
  stop-color: var(--svg-color--e4803e, #E4803E);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vs2_45bjo {
  d: path("M9.647 15.212a2.15 2.15 0 0 1-1.183-.404v1.218c0 1.17.696 2.21 1.754 2.642a5.4 5.4 0 0 1-.452-1.544z");
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wtzd4lbuc {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
  stop-opacity: 0;
}

.wxpwi-bdn {
  d: path("m22.829 10.641l-.038-.826c-.014-.999-.84-1.823-1.839-1.865H19.12a3.17 3.17 0 0 1-2.78-1.648s-.169-.393-.268-1.011c-.159-.99.756-1.717 1.746-1.556c1.384.224 3.104.67 4.33 1.47c2.282 1.49 1.883 4.172.68 5.436");
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xn3x1ebqw {
  stop-color: var(--svg-color--ff4b25, #FF4B25);
  stop-opacity: 0;
}

.y9go09bul {
  stroke: var(--svg-color--c25938, #C25938);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M18.291 9.7c.304.326 1.078.854 2.19.78");
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yq9cl_lgn {
  stop-color: var(--svg-color--ef9330, #EF9330);
}

.z_13pt5jn {
  d: path("M13.15 11.754a1.168 1.168 0 0 0-1.125 1.475h2.256q.042-.149.043-.308a1.176 1.176 0 0 0-1.174-1.167");
}

.z_rhz9mhr {
  stop-color: var(--svg-color--c76f5a, #C76F5A);
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
