<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJMbL6d)"><path fill="url(#iYv5GEI)" class="k94kzqrqv"/><path fill="url(#iL7BM0T)" class="k94kzqrqv"/></g><path fill="url(#iRgwWYd)" class="k94kzqrqv"/><path fill="url(#ilsE2Ed)" class="k94kzqrqv"/><g filter="url(#i6vhJze)"><path fill="url(#iGb9ffb)" class="tw5qyo0bq"/></g><g filter="url(#iL95zie)"><path fill="url(#iUdQPqe)" class="zn4w9bbqc"/></g><g filter="url(#i87Zche)"><path fill="url(#iIM9sDb)" class="bcm1b8bur"/></g><g filter="url(#i9dMKwb)"><rect fill="url(#iaypNfj)" class="l4b5_3uns"/><rect fill="url(#iB9sgQc)" class="l4b5_3uns"/></g><rect fill="url(#iWgirte)" class="l4b5_3uns"/><defs><radialGradient id="iYv5GEI" cx="0" cy="0" r="1" gradientTransform="rotate(100.07 4.98 13.803)scale(18.4086 19.2809)" gradientUnits="userSpaceOnUse"><stop class="waudrj8jg"/><stop offset="1" class="kwx4x1bpb"/></radialGradient><radialGradient id="iL7BM0T" cx="0" cy="0" r="1" gradientTransform="rotate(133.199 8.964 12.301)scale(7.03035 11.7786)" gradientUnits="userSpaceOnUse"><stop class="m4u8qubzp"/><stop offset="1" class="fly6w9b5l"/></radialGradient><radialGradient id="iRgwWYd" cx="0" cy="0" r="1" gradientTransform="matrix(4.5625 2.8125 -6.97039 11.3075 6.067 14.188)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="cua32wpwf"/><stop offset="1" class="w85zetb9o"/></radialGradient><radialGradient id="ilsE2Ed" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3125 24.5772 0 16.223 25.25)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="z_ov27bnl"/><stop offset=".98" class="zc57wio6f"/></radialGradient><radialGradient id="iB9sgQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86719 0 0 -1.40625 18.067 8.094)" gradientUnits="userSpaceOnUse"><stop class="uotn_wl4c"/><stop offset="1" class="z3qubw8me"/></radialGradient><radialGradient id="iWgirte" cx="0" cy="0" r="1" gradientTransform="matrix(-5.53125 0 0 -4.43103 18.317 8.422)" gradientUnits="userSpaceOnUse"><stop offset=".695" class="qi7d6gk0h"/><stop offset=".96" class="iwa-8sb3z"/></radialGradient><filter id="iJMbL6d" width="24.563" height="22.086" x="4.442" y="7.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1.5"/><feGaussianBlur stdDeviation="1.75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.321569 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21307"/></filter><filter id="i6vhJze" width="8.648" height="5.708" x="11.849" y="1.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21307"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.364706 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21307" result="effect2_innerShadow_18_21307"/></filter><filter id="iL95zie" width="6.828" height="14.466" x="12.586" y="13.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21307" stdDeviation=".15"/></filter><filter id="i87Zche" width="6.478" height="14.216" x="12.986" y="13.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21307"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".15"/><feGaussianBlur stdDeviation=".11"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21307" result="effect2_innerShadow_18_21307"/></filter><filter id="i9dMKwb" width="5.734" height="2.709" x="13.333" y="6.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.223529 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21307"/></filter><linearGradient id="iGb9ffb" x1="17.477" x2="16.223" y1="3.891" y2="7.367" gradientUnits="userSpaceOnUse"><stop class="l3bmlqbqh"/><stop offset="1" class="za-zw-bny"/></linearGradient><linearGradient id="iUdQPqe" x1="16" x2="16" y1="13.789" y2="26.602" gradientUnits="userSpaceOnUse"><stop class="htl7jxk9j"/><stop offset="1" class="g8oyq5bjb"/></linearGradient><linearGradient id="iIM9sDb" x1="19.661" x2="13.086" y1="21.875" y2="21.875" gradientUnits="userSpaceOnUse"><stop class="hcuhbib2i"/><stop offset="1" class="ifeg8tjhw"/></linearGradient><linearGradient id="iaypNfj" x1="14.13" x2="19.067" y1="8.422" y2="8.422" gradientUnits="userSpaceOnUse"><stop class="zr9_tcf1c"/><stop offset="1" class="spaq_gltu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:money-bag" /></template>
<style>
.bcm1b8bur {
  d: path("M17 14.156a.8.8 0 0 0-1.6 0v.755c0 .18-.12.334-.287.398a3.4 3.4 0 0 0-.808.443a2.83 2.83 0 0 0-1.156 2.326c0 1.06.477 1.828 1.126 2.32c.618.47 1.364.673 1.96.727c.242.022.603.086.902.274c.258.163.515.442.57 1.04c.052.573-.181.913-.485 1.144c-.35.267-.756.351-.86.351c-.24 0-.653-.032-1.003-.221c-.294-.16-.61-.462-.676-1.198a.8.8 0 1 0-1.594.142c.114 1.28.75 2.051 1.507 2.462q.252.135.501.217c.175.06.303.218.303.403v.683a.8.8 0 1 0 1.6 0v-.676c0-.181.122-.337.292-.4c.3-.11.614-.272.9-.49c.665-.507 1.218-1.351 1.108-2.561c-.102-1.121-.664-1.795-1.32-2.21a3.9 3.9 0 0 0-1.625-.546c-.909-.047-1.607-.549-1.607-1.46c0-.502.2-.87.494-1.09c.609-.516 1.644-.446 2.133.202c.216.287.313.603.335.887c.034.44.415.792.856.758c.44-.034.769-.379.735-.82a3.36 3.36 0 0 0-.653-1.75c-.304-.403-.879-.79-1.35-.984a.46.46 0 0 1-.298-.414z");
}

.cua32wpwf {
  stop-color: var(--svg-color--ffa45d, #FFA45D);
}

.fly6w9b5l {
  stop-color: var(--svg-color--ffe065, #FFE065);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g8oyq5bjb {
  stop-color: var(--svg-color--b95940, #B95940);
}

.hcuhbib2i {
  stop-color: var(--svg-color--9d6360, #9D6360);
}

.htl7jxk9j {
  stop-color: var(--svg-color--a6782c, #A6782C);
}

.ifeg8tjhw {
  stop-color: var(--svg-color--724a4d, #724A4D);
}

.iwa-8sb3z {
  stop-color: var(--svg-color--b3624d, #B3624D);
}

.k94kzqrqv {
  d: path("M4.442 20.883c0-6.351 5.149-11.5 11.5-11.5h.563c6.35 0 11.5 5.149 11.5 11.5v.286a8.8 8.8 0 0 1-8.8 8.8h-5.963a8.8 8.8 0 0 1-8.8-8.8z");
}

.kwx4x1bpb {
  stop-color: var(--svg-color--e88340, #E88340);
}

.l3bmlqbqh {
  stop-color: var(--svg-color--f3c048, #F3C048);
}

.l4b5_3uns {
  width: 5.734px;
  height: 2.109px;
  x: 13.333px;
  y: 7.367px;
  rx: 1.051px;
}

.m4u8qubzp {
  stop-color: var(--svg-color--ffe065, #FFE065);
}

.qi7d6gk0h {
  stop-color: var(--svg-color--b3624d, #B3624D);
  stop-opacity: 0;
}

.spaq_gltu {
  stop-color: var(--svg-color--735854, #735854);
}

.tw5qyo0bq {
  d: path("M12.161 4.695c.47.801 1.155 1.829 2.035 2.672h4.055c.88-.843 1.564-1.87 2.035-2.672a.83.83 0 0 0-.353-1.157c-.32-.164-.696-.086-1.007.095c-.702.409-1.107-.073-1.726-1.02c-.311-.476-.786-.501-.977-.504c-.19.003-.665.028-.976.504c-.62.947-1.024 1.429-1.726 1.02c-.311-.181-.687-.259-1.008-.095a.83.83 0 0 0-.352 1.157");
}

.uotn_wl4c {
  stop-color: var(--svg-color--7d5a54, #7D5A54);
}

.w85zetb9o {
  stop-color: var(--svg-color--ffa45d, #FFA45D);
  stop-opacity: 0;
}

.waudrj8jg {
  stop-color: var(--svg-color--f6c93b, #F6C93B);
}

.z_ov27bnl {
  stop-color: var(--svg-color--f3bd46, #F3BD46);
  stop-opacity: 0;
}

.z3qubw8me {
  stop-color: var(--svg-color--7d5a54, #7D5A54);
  stop-opacity: 0;
}

.za-zw-bny {
  stop-color: var(--svg-color--e67a41, #E67A41);
}

.zc57wio6f {
  stop-color: var(--svg-color--917011, #917011);
}

.zn4w9bbqc {
  d: path("M16.8 14.258a.8.8 0 1 0-1.6 0v.755c0 .179-.12.334-.287.398a3.3 3.3 0 0 0-.808.443a2.83 2.83 0 0 0-1.157 2.326c0 1.06.478 1.828 1.127 2.32c.618.47 1.365.672 1.96.726c.242.022.603.087.901.275c.259.163.516.442.57 1.04c.052.572-.18.912-.483 1.143c-.35.267-.757.352-.86.352c-.241 0-.654-.032-1.004-.222c-.294-.16-.61-.461-.676-1.198a.8.8 0 0 0-1.594.143c.114 1.279.75 2.05 1.507 2.462q.252.134.501.217a.43.43 0 0 1 .303.402v.683a.8.8 0 1 0 1.6 0v-.676c0-.18.122-.337.292-.4c.3-.11.614-.272.9-.49c.665-.507 1.218-1.35 1.108-2.56c-.102-1.121-.664-1.796-1.32-2.21a3.9 3.9 0 0 0-1.625-.546c-.909-.047-1.607-.549-1.607-1.461c0-.502.2-.87.494-1.09c.609-.516 1.644-.446 2.133.202c.216.287.313.603.335.888c.034.44.415.791.856.757c.44-.033.769-.378.735-.819a3.36 3.36 0 0 0-.653-1.75c-.304-.404-.879-.79-1.35-.984a.46.46 0 0 1-.298-.414z");
}

.zr9_tcf1c {
  stop-color: var(--svg-color--834b41, #834B41);
}

</style>
