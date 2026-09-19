<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="yqe8cvbij"/><path fill="url(#iqacLmc)" class="f_z8cfvlr"/><path fill="url(#ige98Wc)" class="f_z8cfvlr"/><g clip-rule="evenodd" filter="url(#iZhspwc)" class="d2kvgvbvc"><path fill="url(#iWzdOFc)" class="zn6fflswm"/><path fill="url(#iA0oRqd)" class="zn6fflswm"/><path fill="url(#iBcWYnc)" class="zn6fflswm"/></g><g filter="url(#im7OmLW)" class="n52mgrb1s"><path stroke="url(#iYQ6rUc)" class="b-nqe1gto"/></g><g filter="url(#iUGRGnd)"><path fill="url(#ihs8TZc)" class="z__0s3qzl"/></g><g filter="url(#i6C0Fnb)"><path fill="url(#i4JPIcc)" class="t_45jmbbn"/><path fill="url(#ipASVkc)" class="t_45jmbbn"/><path fill="url(#iPpGyNc)" class="t_45jmbbn"/></g><g clip-rule="evenodd" filter="url(#ioEGprd)" class="d2kvgvbvc"><path fill="url(#ifZAxvd)" class="j66k0tb6d"/><path fill="url(#iG6IOGc)" class="j66k0tb6d"/></g><g clip-rule="evenodd" filter="url(#iOy6Hce)" class="d2kvgvbvc"><path fill="url(#iugH65d)" class="ooz8hzhwx"/><path fill="url(#ixI49nY)" class="ooz8hzhwx"/></g><g clip-rule="evenodd" filter="url(#i46Wdir)" class="d2kvgvbvc"><path fill="url(#ilBlWze)" class="bhg2bxbzz"/><path fill="url(#iGulQvd)" class="bhg2bxbzz"/></g><g clip-rule="evenodd" filter="url(#idv3V2h)" class="d2kvgvbvc"><path fill="url(#i3y9ucb)" class="u0eljybtm"/><path fill="url(#iNKQdMc)" class="u0eljybtm"/></g><g clip-rule="evenodd" filter="url(#imzUhQe)" class="d2kvgvbvc"><path fill="url(#iQFUPtj)" class="c87pnwxgt"/><path fill="url(#iMuWdvS)" class="c87pnwxgt"/></g><g clip-rule="evenodd" filter="url(#ij0hAOe)" class="d2kvgvbvc"><path fill="url(#iRgh4Hf)" class="ioiksvygw"/><path fill="url(#iHDzrRb)" class="ioiksvygw"/></g><g clip-rule="evenodd" filter="url(#i24Pz1c)" class="d2kvgvbvc"><path fill="url(#iaC6ljb)" class="tbdtm4bwe"/><path fill="url(#iQ17Uyd)" class="tbdtm4bwe"/></g><g clip-rule="evenodd" filter="url(#i6JVDpe)" class="d2kvgvbvc"><path fill="url(#ikj0hyJ)" class="rvv-bym9q"/><path fill="url(#ieeNj1d)" class="rvv-bym9q"/></g><path fill="url(#ih6JZhb)" class="dtjymbcue"/><path fill="url(#iCs4Bfd)" class="dtjymbcue"/><path fill="url(#iXP1zad)" class="fii_34b0m"/><path fill="url(#is2XsCs)" class="fii_34b0m"/><path fill="url(#i9JQJgd)" class="ysk157bzr"/><defs><linearGradient id="iWzdOFc" x1="16" x2="16" y1="1.933" y2="26.933" gradientUnits="userSpaceOnUse"><stop class="gv73esrqv"/><stop offset="1" class="s65ur9b_g"/></linearGradient><linearGradient id="iA0oRqd" x1="16.633" x2="16.633" y1="26.933" y2="25.659" gradientUnits="userSpaceOnUse"><stop class="dl43w3b7f"/><stop offset="1" class="s-u27s8tl"/></linearGradient><linearGradient id="iBcWYnc" x1="28.091" x2="21.358" y1="1.933" y2="8.59" gradientUnits="userSpaceOnUse"><stop class="fzy_f-bfj"/><stop offset="1" class="o9okv2b6o"/></linearGradient><linearGradient id="iYQ6rUc" x1="9.077" x2="23.248" y1="18.213" y2="6.581" gradientUnits="userSpaceOnUse"><stop class="uz_1ctmag"/><stop offset=".286" class="psbnbyhmw"/><stop offset=".865" class="psbnbyhmw"/><stop offset="1" class="ggvs2lbho"/></linearGradient><linearGradient id="ihs8TZc" x1="17.583" x2="17.583" y1="9.273" y2="14.523" gradientUnits="userSpaceOnUse"><stop class="htw5otbhz"/><stop offset="1" class="ry3rqtbny"/></linearGradient><linearGradient id="i4JPIcc" x1="4.081" x2="26.081" y1="29.933" y2="29.933" gradientUnits="userSpaceOnUse"><stop class="y-y-27byy"/><stop offset="1" class="heb9e-0el"/></linearGradient><linearGradient id="iPpGyNc" x1="16.01" x2="16.01" y1="26.715" y2="27.415" gradientUnits="userSpaceOnUse"><stop class="f8p83e9mz"/><stop offset="1" class="qh76abcgk"/></linearGradient><linearGradient id="ifZAxvd" x1="16.01" x2="16.01" y1="4.933" y2="6.323" gradientUnits="userSpaceOnUse"><stop class="n-vr_re5c"/><stop offset="1" class="a0ynbmbne"/></linearGradient><linearGradient id="iugH65d" x1="16.01" x2="16.01" y1="18.963" y2="20.353" gradientUnits="userSpaceOnUse"><stop class="n-vr_re5c"/><stop offset="1" class="a0ynbmbne"/></linearGradient><linearGradient id="ilBlWze" x1="23.02" x2="23.02" y1="12.453" y2="13.148" gradientUnits="userSpaceOnUse"><stop class="n-vr_re5c"/><stop offset="1" class="a0ynbmbne"/></linearGradient><linearGradient id="i3y9ucb" x1="8.99" x2="8.99" y1="12.453" y2="13.148" gradientUnits="userSpaceOnUse"><stop class="n-vr_re5c"/><stop offset="1" class="a0ynbmbne"/></linearGradient><linearGradient id="iQFUPtj" x1="20.97" x2="20.97" y1="7.133" y2="8.322" gradientUnits="userSpaceOnUse"><stop class="n-vr_re5c"/><stop offset="1" class="a0ynbmbne"/></linearGradient><linearGradient id="iRgh4Hf" x1="11.045" x2="11.045" y1="17.053" y2="18.242" gradientUnits="userSpaceOnUse"><stop class="n-vr_re5c"/><stop offset="1" class="a0ynbmbne"/></linearGradient><linearGradient id="iaC6ljb" x1="20.97" x2="20.97" y1="17.053" y2="18.242" gradientUnits="userSpaceOnUse"><stop class="n-vr_re5c"/><stop offset="1" class="a0ynbmbne"/></linearGradient><linearGradient id="ikj0hyJ" x1="11.045" x2="11.045" y1="7.133" y2="8.322" gradientUnits="userSpaceOnUse"><stop class="n-vr_re5c"/><stop offset="1" class="a0ynbmbne"/></linearGradient><linearGradient id="ih6JZhb" x1="15.51" x2="16.51" y1="10.84" y2="10.84" gradientUnits="userSpaceOnUse"><stop class="jexd0dd3f"/><stop offset="1" class="jw4k3dqse"/></linearGradient><linearGradient id="iXP1zad" x1="17.538" x2="21.01" y1="12.857" y2="12.857" gradientUnits="userSpaceOnUse"><stop class="jexd0dd3f"/><stop offset="1" class="jw4k3dqse"/></linearGradient><radialGradient id="iqacLmc" cx="0" cy="0" r="1" gradientTransform="rotate(-45.292 27.777 -4.158)scale(13.5048)" gradientUnits="userSpaceOnUse"><stop class="zv00x1bzy"/><stop offset="1" class="wbhsqg-vx"/></radialGradient><radialGradient id="ige98Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-28.664 37.718 -9.37)scale(17.4583 13.3084)" gradientUnits="userSpaceOnUse"><stop offset=".936" class="hiow-nbmm"/><stop offset=".984" class="pr5sgfbdi"/></radialGradient><radialGradient id="ipASVkc" cx="0" cy="0" r="1" gradientTransform="matrix(27.6191 0 0 13.754 2.01 28.433)" gradientUnits="userSpaceOnUse"><stop offset=".974" class="i86geep7n"/><stop offset="1" class="ud-o1nd2u"/></radialGradient><radialGradient id="iG6IOGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96875 -.44401 0 16.159 5.808)" gradientUnits="userSpaceOnUse"><stop class="ml8qt_yfh"/><stop offset="1" class="a70do0byr"/></radialGradient><radialGradient id="ixI49nY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96875 -.44401 0 16.159 19.838)" gradientUnits="userSpaceOnUse"><stop class="ml8qt_yfh"/><stop offset="1" class="a70do0byr"/></radialGradient><radialGradient id="iGulQvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .48438 -.88802 0 23.318 12.89)" gradientUnits="userSpaceOnUse"><stop class="ml8qt_yfh"/><stop offset="1" class="a70do0byr"/></radialGradient><radialGradient id="iNKQdMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .48438 -.88802 0 9.288 12.89)" gradientUnits="userSpaceOnUse"><stop class="ml8qt_yfh"/><stop offset="1" class="a70do0byr"/></radialGradient><radialGradient id="iMuWdvS" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82828 -.75482 0 21.223 7.88)" gradientUnits="userSpaceOnUse"><stop class="ml8qt_yfh"/><stop offset="1" class="a70do0byr"/></radialGradient><radialGradient id="iHDzrRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82828 -.75926 0 11.3 17.8)" gradientUnits="userSpaceOnUse"><stop class="ml8qt_yfh"/><stop offset="1" class="a70do0byr"/></radialGradient><radialGradient id="iQ17Uyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82828 -.75482 0 21.223 17.8)" gradientUnits="userSpaceOnUse"><stop class="ml8qt_yfh"/><stop offset="1" class="a70do0byr"/></radialGradient><radialGradient id="ieeNj1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82828 -.75926 0 11.3 7.88)" gradientUnits="userSpaceOnUse"><stop class="ml8qt_yfh"/><stop offset="1" class="a70do0byr"/></radialGradient><radialGradient id="iCs4Bfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9462 -.6912 0 16.51 9.279)" gradientUnits="userSpaceOnUse"><stop class="so712-kuc"/><stop offset="1" class="ney6n8bmi"/></radialGradient><radialGradient id="is2XsCs" cx="0" cy="0" r="1" gradientTransform="matrix(0 .75696 -1.5326 0 21.01 12.511)" gradientUnits="userSpaceOnUse"><stop class="so712-kuc"/><stop offset="1" class="ney6n8bmi"/></radialGradient><radialGradient id="i9JQJgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84093 1.41183 -1.33203 -1.73687 16.909 12.38)" gradientUnits="userSpaceOnUse"><stop class="ud-o1nd2u"/><stop offset="1" class="fi3c3xb7v"/></radialGradient><filter id="iZhspwc" width="28.8" height="25" x="1.6" y="1.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.184314 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13407"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.435294 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13407" result="effect2_innerShadow_18_13407"/></filter><filter id="im7OmLW" width="20.987" height="20.987" x="5.873" y="2.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13407" stdDeviation=".2"/></filter><filter id="iUGRGnd" width="7.55" height="6.55" x="13.808" y="8.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13407" stdDeviation=".325"/></filter><filter id="i6C0Fnb" width="28.4" height="3.4" x="2.01" y="26.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.564706 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13407"/></filter><filter id="ioEGprd" width="1.4" height="2.4" x="15.21" y="4.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.533333 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13407"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13407" result="shape"/></filter><filter id="iOy6Hce" width="1.4" height="2.4" x="15.21" y="18.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.533333 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13407"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13407" result="shape"/></filter><filter id="i46Wdir" width="2.4" height="1.4" x="21.72" y="12.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.533333 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13407"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13407" result="shape"/></filter><filter id="idv3V2h" width="2.4" height="1.4" x="7.69" y="12.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.533333 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13407"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13407" result="shape"/></filter><filter id="imzUhQe" width="2.1" height="2.11" x="19.82" y="7.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.533333 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13407"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13407" result="shape"/></filter><filter id="ij0hAOe" width="2.11" height="2.11" x="9.89" y="16.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.533333 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13407"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13407" result="shape"/></filter><filter id="i24Pz1c" width="2.1" height="2.11" x="19.82" y="16.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.533333 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13407"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13407" result="shape"/></filter><filter id="i6JVDpe" width="2.11" height="2.11" x="9.99" y="7.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.533333 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_13407"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_13407" result="shape"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mantelpiece-clock" /></template>
<style>
.a0ynbmbne {
  stop-color: var(--svg-color--f8a433, #F8A433);
}

.a70do0byr {
  stop-color: var(--svg-color--ffc06c, #FFC06C);
  stop-opacity: 0;
}

.b-nqe1gto {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.366 22.47c5.465 0 9.894-4.43 9.894-9.894s-4.43-9.893-9.894-9.893c-5.463 0-9.893 4.43-9.893 9.893s4.43 9.894 9.894 9.894Z");
}

.bhg2bxbzz {
  d: path("M22.02 12.953a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1-.5-.5");
}

.c87pnwxgt {
  d: path("M21.67 7.277a.5.5 0 0 1 .006.707l-.7.71a.5.5 0 1 1-.712-.702l.7-.71a.5.5 0 0 1 .707-.005");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dl43w3b7f {
  stop-color: var(--svg-color--612b33, #612B33);
}

.dtjymbcue {
  d: path("M16.01 13.433c-.28 0-.5-.22-.5-.5v-3.5c0-.28.22-.5.5-.5s.5.22.5.5v3.5c0 .28-.23.5-.5.5");
}

.f_z8cfvlr {
  d: path("M16.01 21.933a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.f8p83e9mz {
  stop-color: var(--svg-color--fea102, #FEA102);
}

.fi3c3xb7v {
  stop-color: var(--svg-color--fb9f2f, #FB9F2F);
}

.fii_34b0m {
  d: path("M20.51 13.433H16c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h4.51c.28 0 .5.22.5.5s-.23.5-.5.5");
}

.ft5dv1b6b {
  fill: none;
}

.fzy_f-bfj {
  stop-color: var(--svg-color--c78a7b, #C78A7B);
}

.ggvs2lbho {
  stop-color: var(--svg-color--c4877b, #C4877B);
}

.gv73esrqv {
  stop-color: var(--svg-color--aa6d67, #AA6D67);
}

.heb9e-0el {
  stop-color: var(--svg-color--ffbe45, #FFBE45);
}

.hiow-nbmm {
  stop-color: var(--svg-color--967a97, #967A97);
  stop-opacity: 0;
}

.htw5otbhz {
  stop-color: var(--svg-color--98869f, #98869F);
}

.i86geep7n {
  stop-color: var(--svg-color--ffdf73, #FFDF73);
  stop-opacity: 0.015;
}

.ioiksvygw {
  d: path("M11.754 17.2a.5.5 0 0 1 0 .707l-.71.71a.5.5 0 0 1-.708-.707l.71-.71a.5.5 0 0 1 .708 0");
}

.j66k0tb6d {
  d: path("M16.01 4.933a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5");
}

.jexd0dd3f {
  stop-color: var(--svg-color--322333, #322333);
}

.jw4k3dqse {
  stop-color: var(--svg-color--613460, #613460);
}

.ml8qt_yfh {
  stop-color: var(--svg-color--ffc06c, #FFC06C);
}

.n-vr_re5c {
  stop-color: var(--svg-color--f09d25, #F09D25);
}

.n52mgrb1s {
  opacity: var(--svg-opacity--0-4, 0.4);
}

.ney6n8bmi {
  stop-color: var(--svg-color--6d3f6a, #6D3F6A);
  stop-opacity: 0;
}

.o9okv2b6o {
  stop-color: var(--svg-color--c78a7b, #C78A7B);
  stop-opacity: 0;
}

.ooz8hzhwx {
  d: path("M16.01 18.963a.5.5 0 0 1 .5.5v1a.5.5 0 1 1-1 0v-1a.5.5 0 0 1 .5-.5");
}

.pr5sgfbdi {
  stop-color: var(--svg-color--967a97, #967A97);
}

.psbnbyhmw {
  stop-color: var(--svg-color--a2716c, #A2716C);
  stop-opacity: 0;
}

.qh76abcgk {
  stop-color: var(--svg-color--fea102, #FEA102);
  stop-opacity: 0;
}

.rvv-bym9q {
  d: path("M10.336 7.28a.5.5 0 0 1 .707 0l.71.71a.5.5 0 0 1-.707.707l-.71-.71a.5.5 0 0 1 0-.708");
}

.ry3rqtbny {
  stop-color: var(--svg-color--b791ab, #B791AB);
}

.s-u27s8tl {
  stop-color: var(--svg-color--612b33, #612B33);
  stop-opacity: 0;
}

.s65ur9b_g {
  stop-color: var(--svg-color--724043, #724043);
}

.so712-kuc {
  stop-color: var(--svg-color--6d3f6a, #6D3F6A);
}

.t_45jmbbn {
  d: path("M28.51 26.933h-25c-.83 0-1.5.67-1.5 1.5s.67 1.5 1.5 1.5h25c.83 0 1.5-.67 1.5-1.5s-.67-1.5-1.5-1.5");
}

.tbdtm4bwe {
  d: path("M20.269 17.197a.5.5 0 0 1 .707.005l.7.71a.5.5 0 0 1-.712.702l-.7-.71a.5.5 0 0 1 .005-.707");
}

.u0eljybtm {
  d: path("M7.99 12.953a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1-.5-.5");
}

.ud-o1nd2u {
  stop-color: var(--svg-color--ffdf73, #FFDF73);
}

.uz_1ctmag {
  stop-color: var(--svg-color--a2716c, #A2716C);
}

.wbhsqg-vx {
  stop-color: var(--svg-color--e3d5e8, #E3D5E8);
}

.y-y-27byy {
  stop-color: var(--svg-color--ffb745, #FFB745);
}

.yqe8cvbij {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.01 21.933a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.ysk157bzr {
  d: path("M16.01 14.183a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5");
}

.z__0s3qzl {
  d: path("M16.854 13.773a1.25 1.25 0 1 1-1.646-1.646V9.773c0-.28.22-.5.5-.5s.5.22.5.5v2.354c.288.126.52.358.646.646h3.354c.28 0 .5.22.5.5s-.23.5-.5.5z");
}

.zn6fflswm {
  d: path("M27.01 21.763c0 1.2.97 2.17 2.17 2.17c.46 0 .83.37.82.83v1.34c0 .46-.37.83-.83.83H2.83c-.46 0-.83-.37-.83-.83v-1.34c0-.46.37-.83.83-.83c1.2 0 2.17-.97 2.17-2.17v-8.83h.01c0-.63.05-1.27.16-1.91c1.06-5.98 6.77-9.98 12.75-8.92c5.34.94 9.09 5.59 9.08 10.83h.01zm-2-8.83a9 9 0 1 1-18 0a9 9 0 0 1 18 0");
}

.zv00x1bzy {
  stop-color: var(--svg-color--f8e9fe, #F8E9FE);
}

</style>
