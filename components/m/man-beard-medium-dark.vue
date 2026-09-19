<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iP3liad)"><circle fill="url(#ibXW1xd)" class="ahwqh5mbl"/></g><g filter="url(#iaitqeL)"><circle fill="url(#iejgc4U)" class="b85cddbta"/></g><g filter="url(#ivjCmuc)"><circle fill="url(#iWM1s9d)" class="ha8o8bbel"/><circle fill="url(#iGBZPNb)" class="ha8o8bbel"/></g><g filter="url(#iakf39c)"><circle class="t3n-qwoga"/><circle fill="url(#itUVwtc)" class="vwdisedfh"/><circle fill="url(#isYsHhe)" class="vwdisedfh"/></g><g filter="url(#igvcQOb)"><path fill="url(#inDtLEe)" class="z7vpdd0lg"/><path fill="url(#iOvqldy)" class="z7vpdd0lg"/><path fill="url(#iIWEqNd)" class="z7vpdd0lg"/></g><path fill="url(#iLQHYeb)" class="l036eoxck"/><path fill="url(#iaxCFyP)" class="l036eoxck"/><path fill="url(#ibrteId)" class="l036eoxck"/><path fill="url(#iWkXoGb)" class="l036eoxck"/><g filter="url(#iCCUkip)"><path fill="url(#iYll0Fc)" class="bd6__acgt"/></g><g filter="url(#idZvyNJ)"><path class="uhohc6bhe"/><path fill="url(#ixz1cSc)" class="acmmzn9ed"/><path fill="url(#ihn2MNe)" class="acmmzn9ed"/><path fill="url(#i1GKysb)" class="acmmzn9ed"/><path fill="url(#iS8Q0jd)" class="acmmzn9ed"/></g><g filter="url(#i884tce)"><path class="xmx0kv8xs"/></g><g filter="url(#inOjXsd)"><path class="elxbkrb8y"/><path fill="url(#ixL79nb)" class="x40e-09gx"/><path fill="url(#iprIHbb)" class="x40e-09gx"/><path fill="url(#i0FMBqe)" class="x40e-09gx"/><path fill="url(#i5aCX1b)" class="x40e-09gx"/></g><path fill="url(#iko6uge)" class="x40e-09gx"/><g filter="url(#iaXUiyc)"><path fill="url(#isIwKCd)" class="ibysuqbsv"/></g><path fill="url(#iQBI91d)" class="ibysuqbsv"/><path fill="url(#itajePb)" class="ibysuqbsv"/><path stroke="url(#iTogdho)" class="udt4om94g"/><g filter="url(#ijefYfc)"><path class="dc_mi06fo"/><path fill="url(#iEbpfec)" class="f5y99h3vv"/></g><g filter="url(#ijv1ozk)"><path class="faovu8byt"/><path fill="url(#iYKtDZd)" class="pgluaptry"/></g><path class="ilt101b5s"/><path fill="url(#i6lJCmd)" class="mooectb4q"/><path class="l25ot5b6e"/><g filter="url(#igQWxMM)"><path class="s03s4p35g"/><path fill="url(#inblued)" class="f6zcojm4k"/></g><g filter="url(#iVtXWRc)"><path fill="url(#ink3kLd)" class="ap-q6ibtl"/></g><path class="c-xtwsbpj"/><path fill="url(#ifph4Fc)" class="le9k-pson"/><path class="mz2qeb0nj"/><g filter="url(#i0kms4d)"><path fill="url(#iNIZ49d)" class="vuu8gjgan"/></g><g filter="url(#iVB7bxc)"><ellipse transform="rotate(-27.914 11.367 16.485)" class="ir2he-bmj"/><ellipse fill="url(#isjGJec)" transform="rotate(-27.914 11.367 16.485)" class="aw_lqibcy"/></g><g filter="url(#iEdVXQb)"><path stroke="url(#i8gRydc)" class="or10f8zqk"/></g><g filter="url(#iIQrbkc)"><path stroke="url(#i02BXHe)" class="f99g4hnnt"/></g><g filter="url(#ivKfYxc)"><path stroke="url(#ie99bId)" class="zge46vgve"/></g><defs><radialGradient id="ibXW1xd" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 17.936)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iGBZPNb" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.526 17.441)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="itUVwtc" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.467)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="isYsHhe" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.39 39.162)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iOvqldy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 3 0 20.321 15.564)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iIWEqNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5625 3.1867 0 11.821 15.814)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="ibrteId" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.25 -20.7011 0 15.384 14.627)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="expufxtqh"/><stop offset="1" class="cpvcnac5k"/></radialGradient><radialGradient id="ixz1cSc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4878 -5.51363 2.04463 .55172 24.049 10.278)" gradientUnits="userSpaceOnUse"><stop class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="ihn2MNe" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -65.69 232.03)scale(7.16286 3.85142)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="i1GKysb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.1314 -4.84965 0 15.946 1.895)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iS8Q0jd" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 24.287 1.314)scale(7.1069 11.1342)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="i5aCX1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36719 -1.17969 0 16.556 20.931)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="itajePb" cx="0" cy="0" r="1" gradientTransform="matrix(10.88217 13.48113 -18.75991 15.14329 12.135 15.375)" gradientUnits="userSpaceOnUse"><stop offset=".901" class="nv4ngd99r"/><stop offset="1" class="iwvz51btf"/></radialGradient><radialGradient id="iEbpfec" cx="0" cy="0" r="1" gradientTransform="matrix(.1943 -1.125 3.32822 .57484 20.502 14.049)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iYKtDZd" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 13.793 .551)scale(1.14166 3.37768)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="i6lJCmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.01 16.664)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="inblued" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.911 3.614)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifph4Fc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.873 16.664)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="isjGJec" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.073 2.955)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iejgc4U" x1="7.092" x2="5.898" y1="18.455" y2="18.455" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iWM1s9d" x1="26.859" x2="25.332" y1="15.9" y2="20.63" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="inDtLEe" x1="23.473" x2="9.231" y1="18.662" y2="20.784" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iLQHYeb" x1="5.884" x2="9.392" y1="23.689" y2="23.564" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iaxCFyP" x1="25.017" x2="23.049" y1="22.127" y2="21.939" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iWkXoGb" x1="16" x2="16" y1="28.16" y2="30.117" gradientUnits="userSpaceOnUse"><stop offset=".533" class="m8c2yi15h"/><stop offset="1" class="vbfhreb6b"/></linearGradient><linearGradient id="iYll0Fc" x1="14.955" x2="30.142" y1="13.096" y2="7.658" gradientUnits="userSpaceOnUse"><stop class="y3qu8-b1b"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="ixL79nb" x1="14.335" x2="16.084" y1="19.891" y2="19.891" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iprIHbb" x1="17.696" x2="15.784" y1="20.493" y2="20.465" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="i0FMBqe" x1="16.309" x2="16.309" y1="21.877" y2="20.808" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iko6uge" x1="16.181" x2="16.181" y1="21.955" y2="21.642" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="isIwKCd" x1="8.628" x2="23.068" y1="28.165" y2="24.078" gradientUnits="userSpaceOnUse"><stop offset=".314" class="zw_dreclm"/><stop offset="1" class="t6ufhqbgd"/></linearGradient><linearGradient id="iQBI91d" x1="6.586" x2="9.004" y1="23.053" y2="22.833" gradientUnits="userSpaceOnUse"><stop class="r5hzt4y-e"/><stop offset="1" class="fklwc1-8k"/></linearGradient><linearGradient id="iTogdho" x1="14.182" x2="14.922" y1="24.971" y2="23.801" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="ink3kLd" x1="21.46" x2="20.875" y1="16.764" y2="17.125" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iNIZ49d" x1="13.26" x2="12.675" y1="16.764" y2="17.125" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8gRydc" x1="21.489" x2="20.706" y1="12.774" y2="11.173" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="i02BXHe" x1="11.597" x2="9.379" y1="12.536" y2="11.606" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ie99bId" x1="7.253" x2="7.253" y1="8.779" y2="12.802" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><filter id="iP3liad" width="6.427" height="6.227" x="3.979" y="14.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19841"/></filter><filter id="iaitqeL" width="4.711" height="4.711" x="4.737" y="15.58" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation=".25"/></filter><filter id="ivjCmuc" width="6.477" height="6.477" x="21.72" y="14.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19841"/></filter><filter id="iakf39c" width="4.711" height="4.711" x="22.478" y="15.58" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation=".25"/></filter><filter id="igvcQOb" width="19.345" height="22.68" x="6.327" y="7.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19841"/></filter><filter id="iCCUkip" width="11.918" height="9.719" x="14.263" y="5.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation="1"/></filter><filter id="idZvyNJ" width="23.5" height="15.5" x="4.196" y="1.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19841"/></filter><filter id="i884tce" width="4.782" height="6.5" x="13.11" y="16.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation=".375"/></filter><filter id="inOjXsd" width="4" height="5.5" x="13.946" y="16.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation=".125"/></filter><filter id="iaXUiyc" width="20.086" height="16.516" x="5.936" y="13.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.235294 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19841"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.290196 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_19841" result="effect2_innerShadow_3987_19841"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0509804 0 0 0 0 0.0196078 0 0 0 0 0.0235294 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_19841" result="effect3_innerShadow_3987_19841"/></filter><filter id="ijefYfc" width="5.34" height="3.147" x="18.151" y="11.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19841"/></filter><filter id="ijv1ozk" width="5.341" height="3.147" x="8.551" y="11.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19841"/></filter><filter id="igQWxMM" width="1.294" height="1.125" x="18.727" y="15.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation=".05"/></filter><filter id="iVtXWRc" width="1.316" height="1.357" x="20.38" y="16.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation=".1"/></filter><filter id="i0kms4d" width="1.493" height="1.594" x="12.097" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation=".1"/></filter><filter id="iVB7bxc" width="1.529" height="1.141" x="10.603" y="15.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation=".05"/></filter><filter id="iEdVXQb" width="4.949" height="2.304" x="18.293" y="11.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation=".25"/></filter><filter id="iIQrbkc" width="5.094" height="2.41" x="8.56" y="11.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation=".25"/></filter><filter id="ivKfYxc" width="1.231" height="3.583" x="6.637" y="8.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19841" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-beard-medium-dark" /></template>
<style>
.acmmzn9ed {
  d: path("m24.933 5.855l.8.398c1.4.696 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.592V9.237c0-.497-.4-.895-.8-.995c-1.201-.298-3.702-.795-7.303-.795s-6.102.497-7.302.795c-.5.1-.8.498-.8.995v1.591c0 .597-.2 1.194-.7 1.592l-.3.298c-.4.298-.6.895-.6 1.393c.1 1.093.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.183 2-3.879l.8-.398c.5-.298 1-.696 1.501-1.094l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.994l1.5 1.492c.4.498.9.796 1.5 1.094");
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahwqh5mbl {
  cx: 7.092px;
  cy: 17.936px;
  r: 3.113px;
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.ap-q6ibtl {
  d: path("M21.496 17.22a1.57 1.57 0 0 0-.432-.864l-.484.532l.218.426z");
}

.aw_lqibcy {
  cx: 11.367px;
  cy: 16.485px;
  rx: 0.726px;
  ry: 0.368px;
}

.b85cddbta {
  cx: 7.092px;
  cy: 17.936px;
  r: 1.855px;
}

.bd6__acgt {
  d: path("m23.338 7.447l-5.74 1.913a1.953 1.953 0 0 0 .878 3.788l5.706-.764z");
}

.c-xtwsbpj {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.267c-1.218 0-2.247.84-2.526 1.974a.51.51 0 0 0 .499.636h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.103");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvcnac5k {
  stop-color: var(--svg-color--7d4371, #7D4371);
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dc_mi06fo {
  fill: var(--svg-color--352827, #352827);
  d: path("m22.883 12.863l-.002-.002l-.004-.003l-.008-.006l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 0 0 .31 1.966a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.298q.011.009.015.01a.995.995 0 0 0 1.265-1.536");
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.elxbkrb8y {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.234 17.403l-.991 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.expufxtqh {
  stop-color: var(--svg-color--7d4371, #7D4371);
  stop-opacity: 0;
}

.f5y99h3vv {
  d: path("m22.883 12.863l-.002-.002l-.004-.003l-.008-.006l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 0 0 .31 1.966a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.298q.011.009.015.01a.995.995 0 0 0 1.265-1.536");
}

.f6zcojm4k {
  d: path("M19.891 16.126c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.f99g4hnnt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.31 13.56c.61-.539 1.942-1.107 3.593-.843");
}

.faovu8byt {
  fill: var(--svg-color--352827, #352827);
  d: path("M8.91 12.864v-.002h.002l.004-.004l.008-.006l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 0 1-.31 1.966a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.298l-.015.01a.995.995 0 0 1-1.266-1.535");
}

.fklwc1-8k {
  stop-color: var(--svg-color--4d4341, #4D4341);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.ha8o8bbel {
  cx: 24.833px;
  cy: 17.936px;
  r: 3.113px;
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.ibysuqbsv {
  d: path("m25.672 14.011l-.703 10.2c-.301 3.3-2.51 5.666-6.023 5.666h-6.024C9.41 29.877 7.2 27.51 6.9 24.21l-.663-9.345l3.072 8.045c.1.5.703.6 1.004.3l.803-.7c.703-.6 1.506-.8 2.31-.8h5.019c.903 0 1.706.2 2.309.8l.803.7c.301.3.903.1 1.004-.3zm-12.75 11.7c0 .9.803 1.7 1.807 1.7c.201 0 .301-.2.301-.3v-.1c0-.5.402-.9.904-.9s.903.4.903.9v.1c0 .2.201.3.302.3c.903 0 1.807-.7 1.807-1.7v-1.5c0-.5-.347-.9-1.004-.9h-4.016c-.636 0-1.004.4-1.004.9z");
}

.ilt101b5s {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.268c1.217 0 2.245.84 2.525 1.973a.51.51 0 0 1-.499.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.103");
}

.ir2he-bmj {
  cx: 11.367px;
  cy: 16.485px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.iwvz51btf {
  stop-color: var(--svg-color--4d4a4f, #4D4A4F);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l036eoxck {
  d: path("M6.327 14.11c0-.497.2-1.094.6-1.392l.3-.298c.5-.398.7-.995.7-1.592V9.237c0-.497.301-.895.801-.995c1.2-.298 3.701-.795 7.302-.795s6.102.497 7.302.795c.4.1.8.498.8.995v1.591c0 .597.3 1.194.7 1.592c.937.656.879 1.017.801 1.79c-.1.994-.2 2.685-.2 2.685h.034l-.496 7.382c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6c-.26-3.388-.373-6.785-.683-10.167");
}

.l25ot5b6e {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 17.438c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.le9k-pson {
  d: path("M11.87 15.774a1.664 1.664 0 0 0-1.604 2.103h3.214c.038-.144.061-.288.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m8c2yi15h {
  stop-color: var(--svg-color--8e5b8e, #8E5B8E);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mooectb4q {
  d: path("M20.013 15.774a1.664 1.664 0 0 1 1.604 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.mz2qeb0nj {
  fill: var(--svg-color--000, #000);
  d: path("M12.823 17.438a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .159.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nv4ngd99r {
  stop-color: var(--svg-color--4d4a4f, #4D4A4F);
  stop-opacity: 0;
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.or10f8zqk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.594c.802-.14 2.366-.1 3.449.742");
}

.pgluaptry {
  d: path("M8.91 12.864v-.002h.002l.004-.004l.008-.006l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 0 1-.31 1.966a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.298l-.015.01a.995.995 0 0 1-1.266-1.535");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r5hzt4y-e {
  stop-color: var(--svg-color--4d4341, #4D4341);
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.s03s4p35g {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.126c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.t3n-qwoga {
  cx: 24.833px;
  cy: 17.936px;
  r: 1.855px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.t6ufhqbgd {
  stop-color: var(--svg-color--373234, #373234);
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.udt4om94g {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.613 23.35a.31.31 0 0 0-.37.063a.28.28 0 0 0-.031.364a3.27 3.27 0 0 0 2.734 1.461a3.27 3.27 0 0 0 2.735-1.461a.29.29 0 0 0-.032-.367a.31.31 0 0 0-.369-.06a5 5 0 0 1-2.334.552a5.06 5.06 0 0 1-2.333-.553Z");
}

.uhohc6bhe {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m24.933 5.855l.8.398c1.4.696 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.592V9.237c0-.497-.4-.895-.8-.995c-1.201-.298-3.702-.795-7.303-.795s-6.102.497-7.302.795c-.5.1-.8.498-.8.995v1.591c0 .597-.2 1.194-.7 1.592l-.3.298c-.4.298-.6.895-.6 1.393c.1 1.093.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.183 2-3.879l.8-.398c.5-.298 1-.696 1.501-1.094l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.994l1.5 1.492c.4.498.9.796 1.5 1.094");
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vbfhreb6b {
  stop-color: var(--svg-color--8e5b8e, #8E5B8E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vuu8gjgan {
  d: path("M13.39 17.243c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.vwdisedfh {
  cx: 24.833px;
  cy: 17.936px;
  r: 1.855px;
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.x40e-09gx {
  d: path("m15.234 17.403l-.991 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xmx0kv8xs {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.433 17.708l-1.53 3.17c-.19.651.266 1.303.91 1.303h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y3qu8-b1b {
  stop-color: var(--svg-color--a27b71, #A27B71);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z7vpdd0lg {
  d: path("M6.436 16.793q.045.003.091.003s-.1-1.591-.2-2.685c0-.498.2-1.095.6-1.393l.3-.298c.5-.398.7-.995.7-1.592V9.237c0-.497.301-.895.801-.995c1.2-.298 3.701-.795 7.302-.795s6.102.497 7.302.795c.4.1.8.498.8.995v1.591c0 .597.3 1.194.7 1.592c.937.656.879 1.017.801 1.79c-.1.994-.2 2.685-.2 2.685h.034l-.496 7.382c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6z");
}

.zge46vgve {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.493 8.963v1.674c-.014.277-.131.897-.481 1.16");
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zw_dreclm {
  stop-color: var(--svg-color--1d1223, #1D1223);
}

</style>
