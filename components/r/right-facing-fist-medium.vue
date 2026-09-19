<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ioeoHic)" transform="matrix(-1 0 0 1 24.164 15.76)" class="njm0dpb1e"/><g filter="url(#iqKK2vx)"><path fill="url(#iAYPNSc)" class="qr1na-b7r"/></g><g filter="url(#ivUQt1d)"><path fill="url(#icc8fed)" clip-rule="evenodd" class="kw3mnbchn"/><path fill="url(#iQkcLcc)" clip-rule="evenodd" class="kw3mnbchn"/></g><path fill="url(#iRCRnpx)" clip-rule="evenodd" class="kw3mnbchn"/><path fill="url(#imiSD4c)" clip-rule="evenodd" class="kw3mnbchn"/><path fill="url(#iAo2Okd)" clip-rule="evenodd" class="kw3mnbchn"/><path fill="url(#i2ty33b)" clip-rule="evenodd" class="kw3mnbchn"/><path fill="url(#iEwcDgb)" clip-rule="evenodd" class="kw3mnbchn"/><path fill="url(#iGD5GUd)" clip-rule="evenodd" class="kw3mnbchn"/><path fill="url(#iIDQpdd)" class="rsab_5bof"/><path fill="url(#iadFNpe)" class="rsab_5bof"/><path fill="url(#iIDQpdd)" class="v1b076bte"/><path fill="url(#iadFNpe)" class="v1b076bte"/><g filter="url(#inkD5Ag)"><path stroke="url(#i1enQWd)" class="kq9kmx-an"/></g><g filter="url(#i0HvuIb)"><path stroke="url(#igw9Ewe)" class="sq5326opg"/></g><g filter="url(#ilm7oed)"><path fill="url(#ijISgpe)" class="dwn4as8oz"/></g><g filter="url(#iVuTHad)"><path stroke="url(#iKdHiua)" class="sz2tfbb2d"/></g><g filter="url(#iCgqQte)"><path stroke="url(#idfw6yd)" class="c8lgklb_n"/></g><g filter="url(#i2911Vc)"><path fill="url(#i4OqlcA)" class="r2ch9v3ev"/></g><defs><radialGradient id="ioeoHic" cx="0" cy="0" r="1" gradientTransform="matrix(-3.45455 -2.5004 1.96327 -2.71245 5.915 4.096)" gradientUnits="userSpaceOnUse"><stop class="qdps8mbtm"/><stop offset="1" class="p5s4rac9s"/></radialGradient><radialGradient id="iAYPNSc" cx="0" cy="0" r="1" gradientTransform="matrix(3.34023 1.05914 -1.73617 5.4754 19.024 20.517)" gradientUnits="userSpaceOnUse"><stop class="eozz1fxza"/><stop offset="1" class="xw796478c"/></radialGradient><radialGradient id="icc8fed" cx="0" cy="0" r="1" gradientTransform="matrix(-20.67863 7.07665 -10.92678 -31.92907 25.455 13.359)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="zg6w8vr9q"/><stop offset="1" class="a94521bso"/></radialGradient><radialGradient id="iQkcLcc" cx="0" cy="0" r="1" gradientTransform="matrix(3.38096 -.36661 .1081 .99695 19.243 17.262)" gradientUnits="userSpaceOnUse"><stop class="r6wfzzaxq"/><stop offset="1" class="c0xreibgq"/></radialGradient><radialGradient id="imiSD4c" cx="0" cy="0" r="1" gradientTransform="matrix(2.5387 -3.9178 6.64011 4.30275 12.876 28.172)" gradientUnits="userSpaceOnUse"><stop class="rl59fab7e"/><stop offset="1" class="fcnx3df-v"/></radialGradient><radialGradient id="iAo2Okd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.30621 -8.37322 5.14514 -1.41711 3.6 18.593)" gradientUnits="userSpaceOnUse"><stop class="vmkjby2sn"/><stop offset="1" class="pexnsss6j"/></radialGradient><radialGradient id="iEwcDgb" cx="0" cy="0" r="1" gradientTransform="matrix(.83058 -1.4731 3.39899 1.91646 4.304 20.524)" gradientUnits="userSpaceOnUse"><stop class="w8udzmgxy"/><stop offset="1" class="k68zulbhz"/></radialGradient><radialGradient id="iGD5GUd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53833 -.45955 .38325 -2.95086 22.33 28.615)" gradientUnits="userSpaceOnUse"><stop class="imqhqd88s"/><stop offset="1" class="a04pds-kx"/></radialGradient><radialGradient id="iIDQpdd" cx="0" cy="0" r="1" gradientTransform="matrix(2.62072 -.57328 1.10205 5.03792 18.99 22.922)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="v5zfuqbmh"/><stop offset="1" class="yc8y743dd"/></radialGradient><linearGradient id="iRCRnpx" x1="16" x2="16" y1="6.913" y2="10.814" gradientUnits="userSpaceOnUse"><stop class="ac8gcacvc"/><stop offset="1" class="z49lxrb6c"/></linearGradient><linearGradient id="i2ty33b" x1="1.342" x2="5.98" y1="16.888" y2="17.39" gradientUnits="userSpaceOnUse"><stop class="j9h3gmbwv"/><stop offset="1" class="rbznk1b8q"/></linearGradient><linearGradient id="iadFNpe" x1="22.769" x2="22.769" y1="21.906" y2="28.983" gradientUnits="userSpaceOnUse"><stop class="vwapgmb7r"/><stop offset="1" class="kpn6myhmn"/></linearGradient><linearGradient id="i1enQWd" x1="18.728" x2="19.442" y1="25.585" y2="15.33" gradientUnits="userSpaceOnUse"><stop class="knzb-acqr"/><stop offset="1" class="qjr87mban"/></linearGradient><linearGradient id="igw9Ewe" x1="13.461" x2="16.812" y1="19.585" y2="17.401" gradientUnits="userSpaceOnUse"><stop class="m_l87kbdg"/><stop offset="1" class="euy3l0a2v"/></linearGradient><linearGradient id="ijISgpe" x1="23.163" x2="32.367" y1="16.523" y2="19.385" gradientUnits="userSpaceOnUse"><stop class="ac_q1dmsm"/><stop offset="1" class="xs9_yyquz"/></linearGradient><linearGradient id="iKdHiua" x1="23.885" x2="30.102" y1="22.227" y2="13.558" gradientUnits="userSpaceOnUse"><stop offset=".448" class="x03i574xp"/><stop offset="1" class="bb902dbel"/></linearGradient><linearGradient id="idfw6yd" x1="32.302" x2="22.153" y1="16.116" y2="17.606" gradientUnits="userSpaceOnUse"><stop class="x03i574xp"/><stop offset="1" class="bb902dbel"/></linearGradient><linearGradient id="i4OqlcA" x1="19.206" x2="19.206" y1="17.816" y2="12.118" gradientUnits="userSpaceOnUse"><stop class="ac_q1dmsm"/><stop offset="1" class="xs9_yyquz"/></linearGradient><filter id="iqKK2vx" width="8.486" height="7.397" x="16.653" y="16.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.203922 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3343"/></filter><filter id="ivUQt1d" width="28.891" height="22.295" x="2.055" y="7.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.25"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.337255 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3343"/></filter><filter id="inkD5Ag" width="13.911" height="17.782" x="10.22" y="11.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3343" stdDeviation="1.25"/></filter><filter id="i0HvuIb" width="6.695" height="8.342" x="11.87" y="13.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3343" stdDeviation=".75"/></filter><filter id="ilm7oed" width="9.014" height="12.34" x="21.585" y="10.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3343" stdDeviation="1"/></filter><filter id="iVuTHad" width="9.877" height="12.488" x="20.427" y="11.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3343" stdDeviation=".75"/></filter><filter id="iCgqQte" width="12.979" height="9.001" x="16.383" y="9.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3343" stdDeviation=".75"/></filter><filter id="i2911Vc" width="13.429" height="8.17" x="15.175" y="10.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3343" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:right-facing-fist-medium" /></template>
<style>
.a04pds-kx {
  stop-color: var(--svg-color--c59883, #C59883);
  stop-opacity: 0;
}

.a94521bso {
  stop-color: var(--svg-color--8e6a5c, #8E6A5C);
}

.ac_q1dmsm {
  stop-color: var(--svg-color--9a6865, #9A6865);
}

.ac8gcacvc {
  stop-color: var(--svg-color--a98a71, #A98A71);
}

.bb902dbel {
  stop-color: var(--svg-color--d8ad98, #D8AD98);
  stop-opacity: 0;
}

.c0xreibgq {
  stop-color: var(--svg-color--704050, #704050);
  stop-opacity: 0;
}

.c8lgklb_n {
  stroke-linecap: round;
  d: path("M18.383 11.42h5.979a3 3 0 0 1 3 3v2");
}

.dwn4as8oz {
  d: path("m26.002 12.353l-2.417 3.933c1.3 1.372.685 3.563.302 4.407H28.6v-8.34z");
}

.eozz1fxza {
  stop-color: var(--svg-color--7a5444, #7A5444);
}

.euy3l0a2v {
  stop-color: var(--svg-color--d0a690, #D0A690);
  stop-opacity: 0;
}

.fcnx3df-v {
  stop-color: var(--svg-color--94557b, #94557B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.imqhqd88s {
  stop-color: var(--svg-color--c59883, #C59883);
}

.j9h3gmbwv {
  stop-color: var(--svg-color--9a7567, #9A7567);
}

.k68zulbhz {
  stop-color: var(--svg-color--9a658b, #9A658B);
  stop-opacity: 0;
}

.knzb-acqr {
  stop-color: var(--svg-color--dbab96, #DBAB96);
}

.kpn6myhmn {
  stop-color: var(--svg-color--995b87, #995B87);
}

.kq9kmx-an {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.72 15.306c-.05 1.77 2.53 8.037 6.91 10.782");
}

.kw3mnbchn {
  fill-rule: evenodd;
  d: path("M24.445 7.931a5.5 5.5 0 0 1 5.5 5.5v5.625h-.004v.399c.01.724-.205 2.58-1.043 3.805c-1.046 1.53-2.859 2.75-4.64 2.75h-2.104c.075.28.102.572.134.92l.001.017c0 1.023-.437 2.563-2.64 3c-.985.148-2-.273-2.829-.93a91 91 0 0 1-1.961-1.64c-.27-.229-.515-.437-.703-.594l-.129-.11c-.357-.31-.862-.746-1.472-.788c-.835-.058-2.42-.38-4.352-2.22c-.78-.742-1.4-1.748-1.755-2.321a10 10 0 0 0-.221-.35q-.08-.117-.138-.212c-.235-.374-.328-.523-1.331-.523l.007-.007h-.71a2 2 0 0 1-2-2v-8.32a2 2 0 0 1 2-2zm-7.302 12.3c-.273-.474-.686-1.271-.87-1.917c-.273-.96.24-1.07.485-1.117c.37-.07.942-.062 1.536-.053c.201.003.405.006.604.006q.357.001.758.005c1.227.012 2.667.026 3.399-.192c.133.065.398.317.398.804v.1c.002.583.004 1.208-.476 1.533c-.178.12-.531.147-.965.18c-.487.036-1.075.08-1.631.273h-.002l-.062.023a2.8 2.8 0 0 0-.701.374a3.33 3.33 0 0 0-1.228 1.742c-.702-.82-1.131-1.54-1.228-1.752z");
}

.m_l87kbdg {
  stop-color: var(--svg-color--d0a690, #D0A690);
}

.njm0dpb1e {
  d: path("M0 0h9.563v7.109H0z");
}

.p5s4rac9s {
  stop-color: var(--svg-color--482a25, #482A25);
}

.pexnsss6j {
  stop-color: var(--svg-color--9b726a, #9B726A);
  stop-opacity: 0;
}

.qdps8mbtm {
  stop-color: var(--svg-color--694643, #694643);
}

.qjr87mban {
  stop-color: var(--svg-color--dbab96, #DBAB96);
  stop-opacity: 0;
}

.qr1na-b7r {
  d: path("M22.308 18.692a4.8 4.8 0 0 0-.066-1.823h2.797v7.297h-6.703c-1.078 0-1.898-1.61-1.633-2.844c.266-1.234 1.432-2.277 2.711-2.203c.963.055 1.893.017 2.524-.073a.43.43 0 0 0 .37-.354");
}

.r2ch9v3ev {
  d: path("M17.175 12.353h9.429l-1.565 4.17h-7.864z");
}

.r6wfzzaxq {
  stop-color: var(--svg-color--704050, #704050);
}

.rbznk1b8q {
  stop-color: var(--svg-color--9a7567, #9A7567);
  stop-opacity: 0;
}

.rl59fab7e {
  stop-color: var(--svg-color--94557b, #94557B);
}

.rsab_5bof {
  d: path("M29.945 16.994v2.062h-.004v.399c.01.724-.205 2.58-1.043 3.805c-.818 1.197-2.105 2.203-3.479 2.585c-.372.1-.75.155-1.126.155h-2.141c-.082-.293-.328-.887-.968-1.465c-.116-.11-.341-.299-.62-.531c-.692-.578-1.642-1.268-2.181-2.006c.141-.47.509-1.232 1.233-1.748a2.8 2.8 0 0 1 .763-.397h.002c.556-.193 1.144-.237 1.631-.274c.434-.032.787-.059.965-.179c.48-.325.478-.95.476-1.532v-.1c0-.43-.206-.677-.346-.774z");
}

.sq5326opg {
  stroke-linecap: round;
  d: path("M16.565 15.256c-.492-.07-1.647.085-2.322 1.267c-.676 1.183-.282 2.534 0 3.062");
}

.sz2tfbb2d {
  stroke-linecap: round;
  d: path("M22.427 21.92h2.877a3 3 0 0 0 3-3v-5.488");
}

.v1b076bte {
  d: path("m22.939 16.994l-.036.008l.011-.008z");
}

.v5zfuqbmh {
  stop-color: var(--svg-color--875e4a, #875E4A);
}

.vmkjby2sn {
  stop-color: var(--svg-color--9b726a, #9B726A);
}

.vwapgmb7r {
  stop-color: var(--svg-color--995b87, #995B87);
  stop-opacity: 0;
}

.w8udzmgxy {
  stop-color: var(--svg-color--9a658b, #9A658B);
}

.x03i574xp {
  stop-color: var(--svg-color--d8ad98, #D8AD98);
}

.xs9_yyquz {
  stop-color: var(--svg-color--9a6865, #9A6865);
  stop-opacity: 0;
}

.xw796478c {
  stop-color: var(--svg-color--4a2b22, #4A2B22);
}

.yc8y743dd {
  stop-color: var(--svg-color--875e4a, #875E4A);
  stop-opacity: 0;
}

.z49lxrb6c {
  stop-color: var(--svg-color--a98a71, #A98A71);
  stop-opacity: 0;
}

.zg6w8vr9q {
  stop-color: var(--svg-color--caa386, #CAA386);
}

</style>
