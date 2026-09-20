<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jwx0ufb_g"/><path clip-rule="evenodd" class="mz98qzbmu"/><path fill="url(#SVGKxfeNdEg)" class="rxtsihb9n"/><defs><linearGradient id="SVGKxfeNdEg" x1="11.999" x2="11.999" y1="5.786" y2="16.5" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".458" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ronin" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jwx0ufb_g {
  fill: var(--svg-color--000, #000);
  d: path("m18.171 3l-.098.264l-.323.844l-.214.545c-1.627 4.08-2.893 6.018-4.239 6.018a2.42 2.42 0 0 1-1.828-.759l-.172-.158c-.427-.4-.607-.498-1.019-.498c-.214 0-.598.277-1.083.927a16.6 16.6 0 0 0-1.648 2.979l-.054.122h5.772l-.719 1.515h-5.39V21H5.572V3zm-2.246 1.512H7.157v5.998c1.05-1.847 2.049-2.774 3.123-2.774a2.58 2.58 0 0 1 1.948.793l.177.163c.4.373.553.459.894.459c.375 0 1.373-1.605 2.626-4.64");
}

.mz98qzbmu {
  fill: var(--svg-color--004de5, #004de5);
  fill-rule: evenodd;
  d: path("M5.571 4.385V15.49a1.38 1.38 0 0 0 .522 1.08l5.255 4.202a1.045 1.045 0 0 0 1.303 0l5.256-4.202a1.38 1.38 0 0 0 .521-1.08V4.385c0-.368-.146-.72-.407-.98A1.4 1.4 0 0 0 17.038 3H6.961a1.384 1.384 0 0 0-1.39 1.385");
}

.rxtsihb9n {
  d: path("M15.747 9.417v-2.42c0-.322-.126-.63-.351-.856a1.2 1.2 0 0 0-.848-.355H9.449c-.318 0-.623.128-.848.355a1.22 1.22 0 0 0-.351.855v7.023a1.22 1.22 0 0 0 .45.944l1.856 1.504a.148.148 0 0 0 .221-.037a.15.15 0 0 0 .023-.081v-4.966q.001-.062.044-.107a.15.15 0 0 1 .106-.044h1.35a.91.91 0 0 1 .9.908v4.209a.15.15 0 0 0 .085.136a.15.15 0 0 0 .159-.018l1.856-1.504a1.21 1.21 0 0 0 .45-.944v-2.182c0-.321-.127-.629-.352-.856a1.2 1.2 0 0 0-.848-.354c.318 0 .622-.129.847-.355c.224-.227.35-.535.35-.855m-3.449.605h-1.35a.15.15 0 0 1-.15-.152V7.148c0-.04.017-.079.045-.107a.15.15 0 0 1 .106-.045h2.099a.15.15 0 0 1 .106.045a.15.15 0 0 1 .044.107v1.966c0 .24-.095.472-.264.642a.9.9 0 0 1-.636.266");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
