<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="cqyygtb7z"/><path stroke="url(#iUg2oGS)" class="gflue9b-v"/><path fill="url(#icfHlQd)" class="kp1zjkaca"/><path fill="url(#i86ScWd)" class="kp1zjkaca"/><path fill="url(#itWamvb)" class="kp1zjkaca"/><path class="ls9pnabpd"/><path fill="url(#iw9UimZ)" class="yxw5irb1m"/><path fill="url(#iONzlJH)" class="yxw5irb1m"/><path fill="url(#iYmkgee)" class="yxw5irb1m"/><g filter="url(#iILVPOe)"><path stroke="url(#iAu3kRb)" class="v380-mx1s"/></g><g filter="url(#i7GpY3A)"><path stroke="url(#iMhP57b)" class="jx1h4pbst"/></g><path class="mskfnp1mn"/><path fill="url(#ii0R5Bd)" class="oxbjj7bcw"/><path fill="url(#iSNMOye)" class="oxbjj7bcw"/><g clip-rule="evenodd" filter="url(#iencUJd)" class="d2kvgvbvc"><path class="fl3gn9bmn"/><path class="u-7e3vc_x"/></g><path clip-rule="evenodd" class="futhvqbai"/><path fill="url(#iYtA1Rb)" clip-rule="evenodd" class="siu6hrsji"/><path fill="url(#iWkQVLe)" clip-rule="evenodd" class="siu6hrsji"/><g filter="url(#iVBoQ1d)"><path class="hwx3dr1_x"/></g><g filter="url(#iVS1FCb)"><path class="oor67_b6b"/></g><g filter="url(#i2Ji5md)"><ellipse class="x34pyhbkb"/></g><g clip-rule="evenodd" filter="url(#iJc6psb)" class="d2kvgvbvc"><path fill="url(#ieFa4Nd)" class="uhz05jbmg"/><path fill="url(#iXkepfU)" class="uhz05jbmg"/></g><g filter="url(#iSoBHSd)"><path fill="url(#i7sg9id)" clip-rule="evenodd" class="ndmxzreuk"/></g><defs><radialGradient id="iUg2oGS" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.78125 -2.62442 0 16.438 7.375)" gradientUnits="userSpaceOnUse"><stop class="ach_iwpct"/><stop offset=".582" class="jp7jnhmcm"/><stop offset="1" class="dcgym9vuo"/></radialGradient><radialGradient id="icfHlQd" cx="0" cy="0" r="1" gradientTransform="rotate(137.703 7.532 11.177)scale(20.6174)" gradientUnits="userSpaceOnUse"><stop class="u3b-5taxs"/><stop offset=".34" class="cq_1jdbgv"/><stop offset=".756" class="xrpb7bbld"/><stop offset="1" class="i5_zs1bse"/></radialGradient><radialGradient id="i86ScWd" cx="0" cy="0" r="1" gradientTransform="rotate(130.885 6.903 11.843)scale(24.6355 14.1886)" gradientUnits="userSpaceOnUse"><stop class="kk-qm8bzi"/><stop offset=".733" class="z_hon2bvl"/><stop offset="1" class="bas7juw_p"/></radialGradient><radialGradient id="itWamvb" cx="0" cy="0" r="1" gradientTransform="rotate(67.051 -6.593 17.196)scale(7.53378 7.7933)" gradientUnits="userSpaceOnUse"><stop class="mtr7cve3q"/><stop offset="1" class="u4gsc0bzv"/></radialGradient><radialGradient id="iw9UimZ" cx="0" cy="0" r="1" gradientTransform="matrix(11.06253 1.4725 -.40707 3.05823 18.688 11.188)" gradientUnits="userSpaceOnUse"><stop class="ob_7u7v_f"/><stop offset="1" class="jucd5lb7l"/></radialGradient><radialGradient id="iONzlJH" cx="0" cy="0" r="1" gradientTransform="matrix(-7.5 1.87497 -.7347 -2.93888 23.5 9.063)" gradientUnits="userSpaceOnUse"><stop class="o1uhemixi"/><stop offset=".574" class="jeg6kru2w"/><stop offset="1" class="l7oxt6vjh"/></radialGradient><radialGradient id="iYmkgee" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 1.62498 -.76158 -2.75345 26.563 9)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="uakl1khkp"/><stop offset="1" class="df6k8cc-f"/></radialGradient><radialGradient id="ii0R5Bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.955 21.6683 0 10.25 9.83)" gradientUnits="userSpaceOnUse"><stop class="wo95z_b5w"/><stop offset=".82" class="tqa6ribii"/></radialGradient><radialGradient id="iSNMOye" cx="0" cy="0" r="1" gradientTransform="matrix(2.99752 6.6875 -6.31377 2.83 9.69 7)" gradientUnits="userSpaceOnUse"><stop class="shf431b2l"/><stop offset=".597" class="cme-o0a7l"/><stop offset="1" class="ij_3ffnbn"/></radialGradient><radialGradient id="iYtA1Rb" cx="0" cy="0" r="1" gradientTransform="rotate(-56.348 26.03 -12.15)scale(13.1395 12.6753)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ob_7u7v_f"/><stop offset=".613" class="ypq3m4bvz"/></radialGradient><radialGradient id="iWkQVLe" cx="0" cy="0" r="1" gradientTransform="matrix(2.53125 2.75 -2.55832 2.35482 12.594 13.063)" gradientUnits="userSpaceOnUse"><stop class="jdbhhpbjr"/><stop offset="1" class="iki2scc8f"/></radialGradient><filter id="iILVPOe" width="4.592" height="5.417" x="23.596" y="6.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27554" stdDeviation=".2"/></filter><filter id="i7GpY3A" width="4.889" height="5.167" x="23.159" y="7.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27554" stdDeviation=".2"/></filter><filter id="iencUJd" width="22.375" height="6.25" x="4.344" y="10.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27554" stdDeviation=".5"/></filter><filter id="iVBoQ1d" width="2.3" height="6.456" x="15.256" y="4.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27554" stdDeviation=".5"/></filter><filter id="iVS1FCb" width="1.2" height="5.356" x="14.8" y="5.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27554" stdDeviation=".25"/></filter><filter id="i2Ji5md" width="1.66" height="1.705" x="15.5" y="4.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27554" stdDeviation=".25"/></filter><filter id="iJc6psb" width="10.416" height="3.904" x="15.847" y="11.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27554" stdDeviation=".1"/></filter><filter id="iSoBHSd" width="10.458" height="3.768" x="5.722" y="11.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27554" stdDeviation=".1"/></filter><linearGradient id="iAu3kRb" x1="24.689" x2="30.125" y1="10.719" y2="3.063" gradientUnits="userSpaceOnUse"><stop class="j3l-1ey8t"/><stop offset="1" class="fx5wngbog"/></linearGradient><linearGradient id="iMhP57b" x1="24.408" x2="29.844" y1="10.598" y2="2.941" gradientUnits="userSpaceOnUse"><stop class="j3l-1ey8t"/><stop offset="1" class="fx5wngbog"/></linearGradient><linearGradient id="ieFa4Nd" x1="16.705" x2="17.889" y1="14.126" y2="11.045" gradientUnits="userSpaceOnUse"><stop class="jg1lt_2_u"/><stop offset=".304" class="qfp3ch4tz"/><stop offset=".667" class="hsljiabid"/><stop offset="1" class="vi0xtpbba"/></linearGradient><linearGradient id="iXkepfU" x1="16.406" x2="25.906" y1="14.126" y2="14.126" gradientUnits="userSpaceOnUse"><stop class="i8c78bcgm"/><stop offset=".181" class="cf5co_bkt"/><stop offset=".628" class="mgv96ev6u"/><stop offset="1" class="yy_-5c15t"/></linearGradient><linearGradient id="i7sg9id" x1="15.625" x2="6.334" y1="14.126" y2="14.126" gradientUnits="userSpaceOnUse"><stop class="e_9-2bnri"/><stop offset=".304" class="b-26ikb1z"/><stop offset=".667" class="siuc3ac-q"/><stop offset="1" class="vi0xtpbba"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tomato" /></template>
<style>
.ach_iwpct {
  stop-color: var(--svg-color--98d31d, #98D31D);
}

.b-26ikb1z {
  stop-color: var(--svg-color--90c72e, #90C72E);
}

.bas7juw_p {
  stop-color: var(--svg-color--ac2248, #AC2248);
}

.cf5co_bkt {
  stop-color: var(--svg-color--9cda3d, #9CDA3D);
}

.cme-o0a7l {
  stop-color: var(--svg-color--86b837, #86B837);
  stop-opacity: 0;
}

.cq_1jdbgv {
  stop-color: var(--svg-color--e31b61, #E31B61);
}

.cqyygtb7z {
  stroke: var(--svg-color--8ecb1f, #8ECB1F);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.99 10.42V6");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dcgym9vuo {
  stop-color: var(--svg-color--9dd538, #9DD538);
  stop-opacity: 0;
}

.df6k8cc-f {
  stop-color: var(--svg-color--9dd43e, #9DD43E);
  stop-opacity: 0;
}

.e_9-2bnri {
  stop-color: var(--svg-color--aedd79, #AEDD79);
}

.fl3gn9bmn {
  fill: var(--svg-color--96cb36, #96CB36);
  d: path("M5.344 15.406h5.743c1.704 0 3.234-.747 4.267-1.672c1.016.705 2.71 1.454 4.631 1.454l5.734.468c0-1.514-2.529-2.996-5.634-2.996H16.28c.28-.442.433-.877.43-1.254l-5.733 1.254c-3.115 0-5.633 1.228-5.633 2.746");
}

.ft5dv1b6b {
  fill: none;
}

.futhvqbai {
  fill: var(--svg-color--80af1f, #80AF1F);
  fill-rule: evenodd;
  d: path("M5.75 15.07h5.77a5.65 5.65 0 0 0 4.468-2.187a5.65 5.65 0 0 0 4.472 2.187h5.76c0-3.12-2.54-5.66-5.66-5.66h-9.15c-3.13 0-5.66 2.53-5.66 5.66");
}

.fx5wngbog {
  stop-color: var(--svg-color--bff079, #BFF079);
  stop-opacity: 0;
}

.gflue9b-v {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.99 10.42V6");
}

.hsljiabid {
  stop-color: var(--svg-color--95d432, #95D432);
}

.hwx3dr1_x {
  stroke: var(--svg-color--bff079, #BFF079);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.406 5.625v4.156");
}

.i5_zs1bse {
  stop-color: var(--svg-color--eb307b, #EB307B);
}

.i8c78bcgm {
  stop-color: var(--svg-color--82c11a, #82C11A);
}

.ij_3ffnbn {
  stop-color: var(--svg-color--87b93b, #87B93B);
}

.iki2scc8f {
  stop-color: var(--svg-color--98d120, #98D120);
  stop-opacity: 0;
}

.j3l-1ey8t {
  stop-color: var(--svg-color--bff079, #BFF079);
}

.jdbhhpbjr {
  stop-color: var(--svg-color--97d121, #97D121);
}

.jeg6kru2w {
  stop-color: var(--svg-color--82b632, #82B632);
  stop-opacity: 0;
}

.jg1lt_2_u {
  stop-color: var(--svg-color--84c21c, #84C21C);
}

.jp7jnhmcm {
  stop-color: var(--svg-color--7bb933, #7BB933);
}

.jucd5lb7l {
  stop-color: var(--svg-color--bcf56a, #BCF56A);
  stop-opacity: 0;
}

.jx1h4pbst {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M27.406 7.5c-.198.75-1.281 3.375-3.781 4.063");
}

.kk-qm8bzi {
  stop-color: var(--svg-color--b91b46, #B91B46);
  stop-opacity: 0;
}

.kp1zjkaca {
  d: path("M19.97 9.99H12c-5.53 0-10 4.48-10 10c0 5.53 4.48 10 10 10h7.96c5.53 0 10-4.48 10-10c.01-5.52-4.47-10-9.99-10");
}

.l7oxt6vjh {
  stop-color: var(--svg-color--83ba2d, #83BA2D);
}

.ls9pnabpd {
  fill: var(--svg-color--93cc2e, #93CC2E);
  d: path("M22.21 7h5.76c0 3.13-2.53 5.66-5.66 5.66h-5.76c0-3.13 2.53-5.66 5.66-5.66");
}

.mgv96ev6u {
  stop-color: var(--svg-color--9ad938, #9AD938);
}

.mskfnp1mn {
  fill: var(--svg-color--85ba1f, #85BA1F);
  d: path("M9.64 12.66h5.76C15.4 9.53 12.87 7 9.74 7H3.98c0 3.13 2.53 5.66 5.66 5.66");
}

.mtr7cve3q {
  stop-color: var(--svg-color--d91253, #D91253);
}

.ndmxzreuk {
  fill-rule: evenodd;
  d: path("M14.766 13.734c.535-.431.936-.987 1.214-1.281v-.86c-.264.28-1.015 1.24-1.532 1.655c-.521.42-1.077.793-1.535.954c-.216.075-.617.136-1.153.178c-.526.042-1.158.065-1.819.075a72 72 0 0 1-3.654-.049l-.365.5c.915.037 2.694.07 4.027.05c.666-.01 1.31-.034 1.851-.077c.534-.043.994-.106 1.278-.205a5.9 5.9 0 0 0 1.688-.94");
}

.o1uhemixi {
  stop-color: var(--svg-color--81b335, #81B335);
  stop-opacity: 0;
}

.ob_7u7v_f {
  stop-color: var(--svg-color--bff96a, #BFF96A);
}

.oor67_b6b {
  stroke: var(--svg-color--a2da38, #A2DA38);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.4 5.625v4.156");
}

.oxbjj7bcw {
  d: path("M9.64 12.66h5.76C15.4 9.53 12.87 7 9.74 7H3.98c0 3.13 2.53 5.66 5.66 5.66");
}

.qfp3ch4tz {
  stop-color: var(--svg-color--9bda3b, #9BDA3B);
}

.shf431b2l {
  stop-color: var(--svg-color--84b72d, #84B72D);
  stop-opacity: 0;
}

.siu6hrsji {
  fill-rule: evenodd;
  d: path("M5.75 15.07h5.77a5.65 5.65 0 0 0 4.468-2.187a5.65 5.65 0 0 0 4.472 2.187h5.76c0-3.12-2.54-5.66-5.66-5.66h-9.15c-3.13 0-5.66 2.53-5.66 5.66");
}

.siuc3ac-q {
  stop-color: var(--svg-color--87af45, #87AF45);
}

.tqa6ribii {
  stop-color: var(--svg-color--9bd03c, #9BD03C);
  stop-opacity: 0;
}

.u-7e3vc_x {
  fill: var(--svg-color--b81d25, #B81D25);
  d: path("M5.344 15.406h5.743c1.704 0 3.234-.747 4.267-1.672c1.016.705 2.71 1.454 4.631 1.454l5.734.468c0-1.514-2.529-2.996-5.634-2.996H16.28c.28-.442.433-.877.43-1.254l-5.733 1.254c-3.115 0-5.633 1.228-5.633 2.746");
}

.u3b-5taxs {
  stop-color: var(--svg-color--ff738e, #FF738E);
}

.u4gsc0bzv {
  stop-color: var(--svg-color--d81254, #D81254);
  stop-opacity: 0;
}

.uakl1khkp {
  stop-color: var(--svg-color--9ed347, #9ED347);
}

.uhz05jbmg {
  d: path("M17.281 13.828c-.535-.431-1.015-.937-1.234-1.375v-.984c.264.279 1.228 1.363 1.745 1.78c.521.42 1.077.792 1.535.952c.216.076.617.137 1.153.18c.526.041 1.158.064 1.819.075c1.321.02 2.371-.013 3.28-.05l.483.5a75 75 0 0 1-3.77.05c-.667-.01-1.27.043-1.812 0c-.534-.043-1.055-.153-1.34-.253c-.542-.19-1.323-.443-1.859-.875");
}

.v380-mx1s {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M27.547 7.375c-.198.75-.985 3.625-3.485 4.313");
}

.vi0xtpbba {
  stop-color: var(--svg-color--91cf21, #91CF21);
}

.wo95z_b5w {
  stop-color: var(--svg-color--ade742, #ADE742);
}

.x34pyhbkb {
  cx: 16.33px;
  cy: 5.647px;
  fill: var(--svg-color--cefb8e, #CEFB8E);
  rx: 0.33px;
  ry: 0.353px;
}

.xrpb7bbld {
  stop-color: var(--svg-color--dd456a, #DD456A);
}

.ypq3m4bvz {
  stop-color: var(--svg-color--bdf66a, #BDF66A);
  stop-opacity: 0.17;
}

.yxw5irb1m {
  d: path("M22.21 7h5.76c0 3.13-2.53 5.66-5.66 5.66h-5.76c0-3.13 2.53-5.66 5.66-5.66");
}

.yy_-5c15t {
  stop-color: var(--svg-color--91cf25, #91CF25);
}

.z_hon2bvl {
  stop-color: var(--svg-color--b31e47, #B31E47);
  stop-opacity: 0;
}

</style>
