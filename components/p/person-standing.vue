<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ouw7vqb5h"/><path class="jsybe8ifa"/><path class="lkxsdsb0j"/><path fill="url(#iCbwr8d)" class="z23533p_d"/><path fill="url(#i9eFuwd)" class="z23533p_d"/><path fill="url(#ic8cf9b)" class="z23533p_d"/><path class="vtwjd4b2m"/><path fill="url(#iAvIY1d)" class="bg_y89dup"/><path fill="url(#i2t38Wd)" class="bg_y89dup"/><path fill="url(#iVEbdbb)" class="bg_y89dup"/><path class="re73b6xet"/><path fill="url(#iSKzZDe)" class="zzl9q_jda"/><path fill="url(#iYGcJKd)" class="zzl9q_jda"/><path fill="url(#i2bDogb)" class="zzl9q_jda"/><path class="qes_hkbxf"/><path fill="url(#iwpA6bd)" class="osx_cvdvg"/><path fill="url(#izQrBVc)" class="osx_cvdvg"/><g filter="url(#iiaKmNc)"><path class="dj5vz_4gh"/></g><path fill="url(#ikOkqwJ)" class="dq46or42q"/><path fill="url(#iVYNDee)" class="dq46or42q"/><path fill="url(#i3qcKIy)" class="dq46or42q"/><path fill="url(#in1TjYd)" class="dq46or42q"/><path fill="url(#i36tcdc)" class="dq46or42q"/><g filter="url(#i0SGtle)"><path fill="url(#iglQ6Fe)" class="io8qqi52v"/><path fill="url(#iotG6Zb)" class="io8qqi52v"/></g><path fill="url(#iV0S0Cc)" class="ck6qoaboh"/><path fill="url(#iEq6xqe)" class="j9f8md3ar"/><path fill="url(#iF3Sfoc)" class="j9f8md3ar"/><path fill="url(#ibMQOyc)" class="f9i66ybti"/><path fill="url(#ivwHnGc)" class="f9i66ybti"/><g filter="url(#i7xucoe)"><path fill="url(#iYEGlmv)" class="acab7s5pm"/></g><path fill="url(#iFpBUfe)" class="acab7s5pm"/><path fill="url(#izIYAie)" class="acab7s5pm"/><path fill="url(#i1j895X)" class="acab7s5pm"/><path fill="url(#ihpmOhd)" class="acab7s5pm"/><g filter="url(#iOJyvkb)"><path class="zn2ga590p"/></g><g filter="url(#ihUqj3c)"><path fill="url(#i3r3npb)" class="fvdn1mbcx"/><path fill="url(#iIuqgme)" class="fvdn1mbcx"/><path fill="url(#icuj3tc)" class="fvdn1mbcx"/><path fill="url(#io0xfue)" class="fvdn1mbcx"/></g><g filter="url(#ihE3Qld)"><path stroke="url(#iGLs1GE)" class="eg-0yubhx"/></g><path fill="url(#i7k0LMe)" class="hljpvq-nq"/><g filter="url(#i7VfS3b)"><path fill="url(#iACmruw)" class="znzzfibhh"/><path fill="url(#iA1eOxK)" class="znzzfibhh"/><path fill="url(#iM7Fzme)" class="znzzfibhh"/><path fill="url(#iRweHke)" class="znzzfibhh"/><path fill="url(#ib08Hsd)" class="znzzfibhh"/></g><g filter="url(#i1Wm4Rd)"><path class="lz7rulpzb"/></g><g filter="url(#i8en7RK)"><path class="zcvq7xblg"/></g><g filter="url(#irh2toc)"><path fill="url(#iT0Hiwd)" class="s3mk7l9pw"/><path fill="url(#ixwTf6b)" class="s3mk7l9pw"/></g><g filter="url(#iAWL2ed)"><path fill="url(#izud9yd)" class="i__2wdwby"/><path fill="url(#ibJ0mje)" class="i__2wdwby"/><path fill="url(#ij7qIpb)" class="i__2wdwby"/><path fill="url(#iRhXgLe)" class="i__2wdwby"/><path fill="url(#ig2qzdd)" class="i__2wdwby"/></g><path class="pl07jvber"/><path fill="url(#iXNt1eo)" class="h66rp2bes"/><path class="pvlsvqw2g"/><g filter="url(#idWAU4c)"><path class="qb2xuc1sn"/><path fill="url(#iKILNHd)" class="gp7z865mt"/></g><g filter="url(#iPXJIJd)"><path fill="url(#i3R0u1c)" class="u4sh72bga"/></g><path class="hif0nrjuc"/><path fill="url(#iYZX6Eb)" class="n-ow8kbdy"/><path class="ylnnz5zcs"/><g filter="url(#i1qfEKb)"><path fill="url(#ipI5G2d)" class="k1yj76zbb"/></g><g filter="url(#ikP0IrR)"><ellipse transform="rotate(-27.914 14.877 5.455)" class="nb03v9sdm"/><ellipse fill="url(#iI37oDe)" transform="rotate(-27.914 14.877 5.455)" class="fqifubccu"/></g><path fill="url(#iiAPSAe)" class="rj_ipvw9a"/><path fill="url(#iEwBYnc)" class="rj_ipvw9a"/><path fill="url(#ib2LqZc)" class="rj_ipvw9a"/><path fill="url(#iTiEfJc)" class="bgcj3abgz"/><path fill="url(#i9uuumN)" class="bgcj3abgz"/><g filter="url(#iBzyJWb)"><path class="ao0q_gbbx"/></g><g filter="url(#i5J8HRb)"><path class="di_n6-gli"/></g><g filter="url(#idjkitM)"><path class="vg4ac3s2n"/></g><g filter="url(#idyps9b)"><path class="esnap5btv"/></g><g filter="url(#iF1Mx5d)"><path class="utjcgnnio"/></g><path fill="url(#iB6Yhfe)" class="tfe_aug3p"/><path fill="url(#iVcvQqc)" class="tfe_aug3p"/><g filter="url(#imzb8KB)"><path class="e6urpmbvi"/></g><defs><radialGradient id="iCbwr8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.357 16.63)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="hv_q7gbew"/><stop offset="1" class="o5yx0rbao"/></radialGradient><radialGradient id="i9eFuwd" cx="0" cy="0" r="1" gradientTransform="matrix(.125 3.21875 -.73141 .0284 13.279 16.898)" gradientUnits="userSpaceOnUse"><stop offset=".022" class="se31mfapw"/><stop offset="1" class="j7o0jsb0d"/></radialGradient><radialGradient id="ic8cf9b" cx="0" cy="0" r="1" gradientTransform="rotate(-104.351 14.426 5.197)scale(2.04829 1.02534)" gradientUnits="userSpaceOnUse"><stop class="ef54lsb2t"/><stop offset="1" class="ekf73n8ha"/></radialGradient><radialGradient id="iAvIY1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.872 16.63)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="zs8fg1bme"/><stop offset="1" class="slh_g2biw"/></radialGradient><radialGradient id="i2t38Wd" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 0 0 4.57812 18.67 17.148)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="vkmdc3sjj"/><stop offset="1" class="cw7ntv66c"/></radialGradient><radialGradient id="iVEbdbb" cx="0" cy="0" r="1" gradientTransform="rotate(-71.25 23.826 -3.005)scale(1.79857 .49047)" gradientUnits="userSpaceOnUse"><stop class="yn315pfzg"/><stop offset="1" class="le_psun2r"/></radialGradient><radialGradient id="iSKzZDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98267 0 0 -3.09375 13.513 12.523)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="cn77rwbmc"/><stop offset="1" class="y2mxoh-zc"/></radialGradient><radialGradient id="iYGcJKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.562 8.832)" gradientUnits="userSpaceOnUse"><stop class="y4_ytjb3b"/><stop offset="1" class="wysngjbll"/></radialGradient><radialGradient id="iwpA6bd" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.3125 1.2963 3.62963 18.794 11.976)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="l7g1kibqg"/><stop offset="1" class="d_gvw4b_b"/></radialGradient><radialGradient id="i3qcKIy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 16 18.101)" gradientUnits="userSpaceOnUse"><stop class="rwlxembxd"/><stop offset="1" class="oig4whb0o"/></radialGradient><radialGradient id="in1TjYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.076 28.465)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="i36tcdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.794 28.554)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iotG6Zb" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.427 8.227)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="mdbsecb0y"/><stop offset="1" class="y-nukfwnq"/></radialGradient><radialGradient id="iV0S0Cc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.11133 -1.40894 0 16 8.486)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="w4burac2j"/><stop offset="1" class="tpyprqb_v"/></radialGradient><radialGradient id="iEq6xqe" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 6.724 10.49)scale(1.71876 2.04175)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iF3Sfoc" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 2.722 21.06)scale(.22348 .18985)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="ibMQOyc" cx="0" cy="0" r="1" gradientTransform="matrix(.5984 1.76117 -.80053 .272 13.489 6.384)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="ivwHnGc" cx="0" cy="0" r="1" gradientTransform="matrix(.14295 .44767 -.3927 .1254 13.786 6.38)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iYEGlmv" cx="0" cy="0" r="1" gradientTransform="matrix(-2.34669 0 0 -4.15128 17.24 5.91)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iFpBUfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.5625 6.0783 0 15.892 9.007)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="bkz_cdc-o"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="izIYAie" cx="0" cy="0" r="1" gradientTransform="matrix(-.1807 2.73905 -1.007 -.06643 18.294 5.805)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="i1j895X" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.63466 .7641 0 15.04 5.38)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="ihpmOhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.68914 .89384 0 17.096 5.195)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iGLs1GE" cx="0" cy="0" r="1" gradientTransform="matrix(.15583 -.27806 .80916 .45349 15.473 7.386)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="i7k0LMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32353 1.30163 0 15.979 7.498)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iA1eOxK" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.56715 4.54848 0 13.632 5.2)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iM7Fzme" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.63064 2.88916 0 18.161 5.2)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iRweHke" cx="0" cy="0" r="1" gradientTransform="rotate(-160.666 9.114 -.327)scale(1.95351 1.04038)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="ib08Hsd" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.297 14.747)scale(.77682 1.79875)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iT0Hiwd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.70886 .61657 -.1716 -.47562 16.093 2.314)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="ixwTf6b" cx="0" cy="0" r="1" gradientTransform="matrix(1.44458 -2.28726 2.53404 1.60044 13.541 4.45)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="px2az-bfw"/><stop offset=".233" class="di0k0obbi"/><stop offset="1" class="dswxpyn3c"/></radialGradient><radialGradient id="izud9yd" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -3.35 76.871)scale(1.56176 .87344)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="ibJ0mje" cx="0" cy="0" r="1" gradientTransform="matrix(-.96447 -1.66253 .92718 -.53788 18.281 4.902)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="ij7qIpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.58685 -.98857 .70807 -.42034 18.003 4.768)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iRhXgLe" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 8.9 2.464)scale(2.21505 2.39456)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="ig2qzdd" cx="0" cy="0" r="1" gradientTransform="rotate(107.002 7.755 7.848)scale(.18012 .8235)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="iXNt1eo" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36419 -.57928 0 16.958 5.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iKILNHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10386 -.13384 .18427 -.143 16.855 5.535)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYZX6Eb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3642 -.57931 0 15 5.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iI37oDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00346 -.22127 .26598 -.00416 14.87 5.596)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iEwBYnc" cx="0" cy="0" r="1" gradientTransform="matrix(.28215 1.00697 -.96073 .26919 18.052 5.504)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="ib2LqZc" cx="0" cy="0" r="1" gradientTransform="rotate(-53.92 14.758 -15.03)scale(.60046 .50331)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="i9uuumN" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 4.519 8.377)scale(.95014 .93408)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="iVcvQqc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.566 29.414)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><filter id="iiaKmNc" width="6.169" height="12.453" x="13.016" y="16.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.360784 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_167"/></filter><filter id="i0SGtle" width="6.417" height="7.594" x="12.941" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.415686 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_167"/></filter><filter id="i7xucoe" width="5.088" height="5.74" x="13.706" y="3.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_167"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_167" result="effect2_innerShadow_4002_167"/></filter><filter id="iOJyvkb" width="2.843" height="3.302" x="14.464" y="4.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".5"/></filter><filter id="ihUqj3c" width="1.043" height="1.502" x="15.458" y="5.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".05"/></filter><filter id="ihE3Qld" width="1.745" height=".782" x="15.107" y="6.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".05"/></filter><filter id="i7VfS3b" width="5.778" height="3.727" x="13.09" y="1.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_167"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_167" result="effect2_innerShadow_4002_167"/></filter><filter id="i1Wm4Rd" width="1.105" height=".645" x="16.692" y="4.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_167"/></filter><filter id="i8en7RK" width="1.105" height=".638" x="14.333" y="4.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_167"/></filter><filter id="irh2toc" width="2.931" height="2.645" x="13.261" y="2.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".05"/></filter><filter id="iAWL2ed" width="2.758" height="2.512" x="15.993" y="2.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".05"/></filter><filter id="idWAU4c" width=".463" height=".422" x="16.574" y="5.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".05"/></filter><filter id="iPXJIJd" width=".62" height=".63" x="16.896" y="5.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".1"/></filter><filter id="i1qfEKb" width=".663" height=".687" x="14.901" y="5.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".1"/></filter><filter id="ikP0IrR" width=".519" height=".426" x="14.618" y="5.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".05"/></filter><filter id="iBzyJWb" width=".872" height="1.344" x="13.133" y="5.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".125"/></filter><filter id="i5J8HRb" width=".925" height="1.354" x="17.956" y="5.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".125"/></filter><filter id="idjkitM" width="1.043" height=".484" x="14.315" y="4.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".05"/></filter><filter id="idyps9b" width="1.043" height=".484" x="16.684" y="4.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".05"/></filter><filter id="iF1Mx5d" width="3.316" height="1.848" x="12.434" y="28.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_167"/></filter><filter id="imzb8KB" width="6.594" height="13.766" x="12.841" y="15.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_167" stdDeviation=".5"/></filter><linearGradient id="i2bDogb" x1="12.466" x2="12.466" y1="12.781" y2="12.304" gradientUnits="userSpaceOnUse"><stop class="mea8vgbzb"/><stop offset="1" class="x8_6e5b0q"/></linearGradient><linearGradient id="izQrBVc" x1="19.747" x2="19.747" y1="12.867" y2="12.164" gradientUnits="userSpaceOnUse"><stop class="kidhsabwy"/><stop offset="1" class="i08i0qbub"/></linearGradient><linearGradient id="ikOkqwJ" x1="13.341" x2="13.568" y1="24.226" y2="24.218" gradientUnits="userSpaceOnUse"><stop class="yaaat27jw"/><stop offset="1" class="jursh_bcv"/></linearGradient><linearGradient id="iVYNDee" x1="16" x2="16" y1="16.011" y2="16.445" gradientUnits="userSpaceOnUse"><stop class="j3c7jv70r"/><stop offset="1" class="y3uayvb5s"/></linearGradient><linearGradient id="iglQ6Fe" x1="16" x2="16" y1="9.101" y2="16.062" gradientUnits="userSpaceOnUse"><stop class="hrtvttbtf"/><stop offset="1" class="nua72fb5w"/></linearGradient><linearGradient id="i3r3npb" x1="15.979" x2="16.363" y1="6.281" y2="6.281" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iIuqgme" x1="15.498" x2="15.98" y1="6.211" y2="6.238" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="icuj3tc" x1="15.979" x2="15.979" y1="6.46" y2="6.843" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="io0xfue" x1="15.979" x2="15.979" y1="5.451" y2="5.64" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iACmruw" x1="18.387" x2="13.842" y1="3.367" y2="3.367" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="i3R0u1c" x1="17.307" x2="17.166" y1="5.522" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipI5G2d" x1="15.333" x2="15.192" y1="5.522" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iiAPSAe" x1="18.868" x2="18.326" y1="5.534" y2="6.511" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iTiEfJc" x1="13.353" x2="14.008" y1="5.85" y2="5.793" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iB6Yhfe" x1="18.247" x2="16.5" y1="29.726" y2="29.523" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-standing" /></template>
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

.acab7s5pm {
  d: path("M13.813 7.15a1.76 1.76 0 0 0 1.744 1.53h.847c.883 0 1.629-.653 1.744-1.53c.053-.845.107-1.687.146-2.532a.65.65 0 0 0-.62-.643h-.628c-.428 0-.816-.253-.992-.648a.3.3 0 0 0-.276-.188h-.572c-.828 0-1.5.68-1.5 1.517c0 .835.052 1.657.107 2.494");
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.ao0q_gbbx {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M13.718 5.372a.429.429 0 0 0 .037.843a35 35 0 0 1-.037-.843");
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bg_y89dup {
  d: path("M19.888 20.44c.938-1.981.769-6.258.487-7.823h-1.672c.072 2.425-.155 5.253-.293 6.522a.29.29 0 0 0 .554.15l.117-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.062.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.bgcj3abgz {
  d: path("M13.71 5.075a.722.722 0 0 0 .063 1.436a35 35 0 0 1-.062-1.436");
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bkz_cdc-o {
  stop-color: var(--svg-color--e27426, #E27426);
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

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.ck6qoaboh {
  d: path("M15.129 7.375h1.742v1.351a.871.871 0 0 1-1.742 0z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn77rwbmc {
  stop-color: var(--svg-color--f16440, #F16440);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.cw7ntv66c {
  stop-color: var(--svg-color--d0910c, #D0910C);
  stop-opacity: 0;
}

.d_gvw4b_b {
  stop-color: var(--svg-color--ff391e, #FF391E);
  stop-opacity: 0;
}

.di_n6-gli {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M18.206 6.219q.027-.428.05-.854a.429.429 0 0 1-.05.854");
}

.di0k0obbi {
  stop-color: var(--svg-color--f69727, #F69727);
}

.dj5vz_4gh {
  fill: var(--svg-color--a2859a, #A2859A);
  d: path("m13.016 16.011l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.dq46or42q {
  d: path("m13.016 16.011l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.dswxpyn3c {
  stop-color: var(--svg-color--f69727, #F69727);
  stop-opacity: 0;
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e6urpmbvi {
  fill: var(--svg-color--ac99aa, #AC99AA);
  d: path("m13.84 16.382l.47 11.766h.812v-10.61h2.203v10.61h.672l.438-11.766z");
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.ef54lsb2t {
  stop-color: var(--svg-color--c2821c, #C2821C);
}

.eg-0yubhx {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.979 7.21c-.228 0-.442-.054-.622-.148c-.061-.031-.127.038-.089.094a.85.85 0 0 0 .711.38a.85.85 0 0 0 .71-.38c.04-.058-.027-.125-.088-.094a1.34 1.34 0 0 1-.622.148Z");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.ekf73n8ha {
  stop-color: var(--svg-color--eda82d, #EDA82D);
  stop-opacity: 0;
}

.esnap5btv {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.577 4.628a1.04 1.04 0 0 0-.743-.171");
}

.f9i66ybti {
  d: path("M13.797 6.47a.74.74 0 0 1-.406-.138v.418c0 .4.239.758.602.906a1.8 1.8 0 0 1-.156-.53z");
}

.fqifubccu {
  cx: 14.877px;
  cy: 5.455px;
  rx: 0.174px;
  ry: 0.088px;
}

.ft5dv1b6b {
  fill: none;
}

.fvdn1mbcx {
  d: path("m15.808 5.589l-.24.825c-.048.17.069.34.235.34h.353c.165 0 .282-.173.233-.34l-.238-.825c-.051-.183-.29-.183-.344 0");
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gp7z865mt {
  d: path("M16.93 5.369c.028.038-.032.084-.1.135c-.067.05-.117.086-.146.048s.003-.11.071-.16s.146-.061.174-.023");
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h66rp2bes {
  d: path("M16.96 5.284a.4.4 0 0 1 .385.506h-.774a.402.402 0 0 1 .388-.506");
}

.hif0nrjuc {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.906 5.162a.63.63 0 0 0-.609.475c-.02.078.04.153.12.153h1.002a.103.103 0 0 0 .102-.122a.63.63 0 0 0-.615-.506");
}

.hljpvq-nq {
  d: path("M15.979 7.21c-.228 0-.442-.054-.622-.148c-.061-.031-.127.038-.089.094a.85.85 0 0 0 .711.38a.85.85 0 0 0 .71-.38c.04-.058-.027-.125-.088-.094a1.34 1.34 0 0 1-.622.148");
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hrtvttbtf {
  stop-color: var(--svg-color--ff7325, #FF7325);
}

.hv_q7gbew {
  stop-color: var(--svg-color--e97a06, #E97A06);
}

.i__2wdwby {
  d: path("m18.319 4.902l-.014-.283a.66.66 0 0 0-.63-.64h-.629c-.399 0-.763-.218-.953-.565c0 0 .323-.934.86-.813c.391.088.811.227 1.132.437c.783.51.646 1.43.234 1.864");
}

.i08i0qbub {
  stop-color: var(--svg-color--ff381e, #FF381E);
  stop-opacity: 0;
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

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.io8qqi52v {
  d: path("M12.942 11.527a3.059 3.059 0 1 1 6.117 0v4.441a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.094-.094z");
}

.j3c7jv70r {
  stop-color: var(--svg-color--966d92, #966D92);
}

.j7o0jsb0d {
  stop-color: var(--svg-color--d58816, #D58816);
  stop-opacity: 0;
}

.j9f8md3ar {
  d: path("M18.161 6.47a.74.74 0 0 0 .406-.138v.418c0 .4-.239.758-.602.906q.116-.245.155-.53z");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jsybe8ifa {
  fill: var(--svg-color--c78e18, #C78E18);
  d: path("M19.333 19.16a.22.22 0 0 0 .043-.238h.437l-.32.996c-.262.078-.54.05-.59-.114a.32.32 0 0 1 .074-.3a9 9 0 0 0 .356-.344");
}

.jursh_bcv {
  stop-color: var(--svg-color--a5949b, #A5949B);
  stop-opacity: 0;
}

.k1yj76zbb {
  d: path("M15.364 5.637c0-.13-.105-.215-.134-.241l-.129.125l.08.161z");
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

.kidhsabwy {
  stop-color: var(--svg-color--ff381e, #FF381E);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.l7g1kibqg {
  stop-color: var(--svg-color--ff391e, #FF391E);
}

.le_psun2r {
  stop-color: var(--svg-color--cc952b, #CC952B);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkxsdsb0j {
  fill: var(--svg-color--eaae34, #EAAE34);
  d: path("M12.112 20.44c-.938-1.981-.769-6.258-.487-7.823h1.672c-.072 2.425.039 5.243.177 6.511c.012.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.062.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lz7rulpzb {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M17.655 4.572a.8.8 0 0 0-.309-.185c-.136-.043-.308-.054-.544-.025a.125.125 0 0 0 .03.247c.216-.027.348-.013.44.016a.6.6 0 0 1 .22.135a.125.125 0 0 0 .163-.188");
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdbsecb0y {
  stop-color: var(--svg-color--ff863c, #FF863C);
}

.mea8vgbzb {
  stop-color: var(--svg-color--fb2d18, #FB2D18);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.n-ow8kbdy {
  d: path("M14.998 5.284a.4.4 0 0 0-.386.506h.774a.403.403 0 0 0-.388-.506");
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nb03v9sdm {
  cx: 14.877px;
  cy: 5.455px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.174px;
  ry: 0.088px;
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nua72fb5w {
  stop-color: var(--svg-color--ff4c2e, #FF4C2E);
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o5yx0rbao {
  stop-color: var(--svg-color--f2a31f, #F2A31F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oig4whb0o {
  stop-color: var(--svg-color--867081, #867081);
  stop-opacity: 0;
}

.osx_cvdvg {
  d: path("M20.468 12.66c-.487-2.253-1.629-3.333-3.03-3.828v3.949h2.933a.1.1 0 0 0 .097-.12");
}

.ouw7vqb5h {
  fill: var(--svg-color--bf8011, #BF8011);
  d: path("M12.668 19.16a.22.22 0 0 1-.043-.238h-.438l.32.996c.262.078.54.05.59-.114a.32.32 0 0 0-.074-.3a9 9 0 0 1-.355-.344");
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl07jvber {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.052 5.162c.293 0 .541.202.608.475a.123.123 0 0 1-.12.153h-1a.103.103 0 0 1-.102-.122a.63.63 0 0 1 .615-.506");
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pvlsvqw2g {
  fill: var(--svg-color--000, #000);
  d: path("M16.73 5.685c0-.128.102-.23.23-.23a.228.228 0 0 1 .203.335h-.406a.2.2 0 0 1-.027-.105");
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.px2az-bfw {
  stop-color: var(--svg-color--df8935, #DF8935);
}

.qb2xuc1sn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.93 5.369c.028.038-.032.084-.1.135c-.067.05-.117.086-.146.048s.003-.11.071-.16s.146-.061.174-.023");
}

.qes_hkbxf {
  fill: var(--svg-color--ff7a43, #FF7A43);
  d: path("M20.468 12.66c-.487-2.253-1.629-3.333-3.03-3.828v3.949h2.933a.1.1 0 0 0 .097-.12");
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
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

.re73b6xet {
  fill: var(--svg-color--ff4326, #FF4326);
  d: path("M11.533 12.66c.486-2.253 1.628-3.333 3.03-3.828v3.949H11.63a.1.1 0 0 1-.097-.12");
}

.rj_ipvw9a {
  d: path("M18.188 6.511q.045-.717.083-1.432a.723.723 0 0 1-.083 1.432");
}

.rwlxembxd {
  stop-color: var(--svg-color--8560a3, #8560A3);
}

.s3mk7l9pw {
  d: path("m16.083 3.389l-.03-.062a.3.3 0 0 0-.276-.188h-.571c-.829 0-1.5.68-1.5 1.517v.124c-.153-.117-.344-.362-.344-.758c0-.481.35-.724.574-.88c.063-.043.116-.08.149-.113l.044-.047c.157-.167.437-.463.925-.593q.116-.03.231-.047c.468-.07.808.348.808.821v.22z");
}

.se31mfapw {
  stop-color: var(--svg-color--ad6605, #AD6605);
}

.slh_g2biw {
  stop-color: var(--svg-color--fcb726, #FCB726);
  stop-opacity: 0;
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.tfe_aug3p {
  d: path("M19.567 29.82v.242H16.5v-1.598h1.992c.102.368.575.754.817.915c.186.123.258.3.258.44");
}

.tpyprqb_v {
  stop-color: var(--svg-color--ffb614, #FFB614);
}

.u4sh72bga {
  d: path("M17.316 5.631a.4.4 0 0 0-.104-.207l-.116.128l.052.102z");
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.utjcgnnio {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.434 29.82v.242H15.5v-1.598h-1.992c-.102.368-.574.754-.816.915a.54.54 0 0 0-.258.44");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vg4ac3s2n {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.465 4.648a1.04 1.04 0 0 1 .743-.17");
}

.vkmdc3sjj {
  stop-color: var(--svg-color--bc7a0b, #BC7A0B);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vtwjd4b2m {
  fill: var(--svg-color--ffcc2d, #FFCC2D);
  d: path("M19.888 20.44c.938-1.981.769-6.258.487-7.823h-1.672c.072 2.425-.155 5.253-.293 6.522a.29.29 0 0 0 .554.15l.117-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.062.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.w4burac2j {
  stop-color: var(--svg-color--fa9e1e, #FA9E1E);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.wysngjbll {
  stop-color: var(--svg-color--de5d25, #DE5D25);
  stop-opacity: 0;
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.x8_6e5b0q {
  stop-color: var(--svg-color--fb2d18, #FB2D18);
  stop-opacity: 0;
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.y-nukfwnq {
  stop-color: var(--svg-color--ff863c, #FF863C);
  stop-opacity: 0;
}

.y2mxoh-zc {
  stop-color: var(--svg-color--f16440, #F16440);
}

.y3uayvb5s {
  stop-color: var(--svg-color--966d92, #966D92);
  stop-opacity: 0;
}

.y4_ytjb3b {
  stop-color: var(--svg-color--de5d25, #DE5D25);
}

.yaaat27jw {
  stop-color: var(--svg-color--a5949b, #A5949B);
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.ylnnz5zcs {
  fill: var(--svg-color--000, #000);
  d: path("M15.228 5.685a.23.23 0 0 0-.23-.23a.228.228 0 0 0-.203.335h.406a.2.2 0 0 0 .027-.105");
}

.yn315pfzg {
  stop-color: var(--svg-color--cc952b, #CC952B);
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.z23533p_d {
  d: path("M12.112 20.44c-.938-1.981-.769-6.258-.487-7.823h1.672c-.072 2.425.039 5.243.177 6.511c.012.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.062.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zcvq7xblg {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M14.448 4.523a1.25 1.25 0 0 1 .78-.161a.125.125 0 1 1-.03.247a1 1 0 0 0-.656.149l-.008.005v.001a.124.124 0 0 1-.153-.197z");
}

.zn2ga590p {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.76 5.676l-.284.826c-.05.17.068.34.233.34h.353c.166 0 .283-.173.234-.34l-.239-.826c-.05-.182-.243-.182-.296 0");
}

.znzzfibhh {
  d: path("M18.158 2.927a1.064 1.064 0 0 1 .521 1.606a.7.7 0 0 0-.12.393v.533a.8.8 0 0 0-.3-.12l.035-.721a.65.65 0 0 0-.619-.643h-.628c-.429 0-.817-.253-.993-.648a.3.3 0 0 0-.276-.188h-.572c-.828 0-1.5.68-1.5 1.517l.014.69a.8.8 0 0 0-.323.119v-.54a.7.7 0 0 0-.122-.392a1.07 1.07 0 0 1-.064-1.098c.131-.248.343-.42.583-.505c.258-.092.477-.265.622-.499a1.044 1.044 0 0 1 1.297-.409a.67.67 0 0 0 .536 0a1.044 1.044 0 0 1 1.302.424c.138.229.355.395.607.481");
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.zs8fg1bme {
  stop-color: var(--svg-color--f88e01, #F88E01);
}

.zzl9q_jda {
  d: path("M11.533 12.66c.486-2.253 1.628-3.333 3.03-3.828v3.949H11.63a.1.1 0 0 1-.097-.12");
}

</style>
