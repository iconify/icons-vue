<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zzqoq-bnu"/><path class="z8qapacve"/><circle class="qx8xxpf-m"/><linearGradient id="SVGSWdwDczA" x1="64" x2="64" y1="104.767" y2="22.714" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="lmwksq2ex"/></linearGradient><path fill="url(#SVGSWdwDczA)" class="eq7xr8mnk"/><g class="n1mjunbsu"><path class="y42uin-_f"/><path class="j5307g9ce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:mobile-phone" /></template>
<style>
.eq7xr8mnk {
  d: path("M39.21 22.71h49.57v82.05H39.21z");
}

.j5307g9ce {
  d: path("M81.91 110.1h-.83v-1.8h-3.55v-.83h4.38z");
}

.lmwksq2ex {
  stop-color: var(--svg-color--00a0d6, #00a0d6);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.qx8xxpf-m {
  cx: 83.89px;
  cy: 10.49px;
  r: 1.99px;
  fill: var(--svg-color--fff, #fff);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.y42uin-_f {
  d: path("M48.37 108.93v.7l-1.53-1.11l1.53-1.12v.7h.88c1.72 0 2.83.51 2.83 1.99c0 1.49-1.11 2-2.83 2h-1.98v-.83h1.98c1.46 0 2-.32 2-1.17c0-.84-.53-1.16-2-1.16zm18.54 2.88h-5.73v-2.89l2.87-1.21l2.87 1.21v2.89zm-4.9-.84h4.07v-1.51l-2.03-.86l-2.04.86zm18.54.84h-4.8v-3.04h4.8zm-3.96-.84h3.14v-1.37h-3.14z");
}

.z8qapacve {
  fill: var(--svg-color--fff, #fff);
  d: path("M69.57 10.75H58.44a1.04 1.04 0 1 1 0-2.08h11.13c.58 0 1.04.46 1.04 1.04c0 .57-.46 1.04-1.04 1.04");
}

.zzqoq-bnu {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M88.46 6.33C84.22 4.43 71.85 3.22 64 3.22c-7.84 0-20.23 1.21-24.46 3.11c-4.15 1.86-5.82 5.54-5.82 8.99v97.35c0 3.46 1.67 7.13 5.82 8.99c4.23 1.9 16.62 3.11 24.46 3.11c7.85 0 20.22-1.21 24.46-3.11c4.15-1.86 5.82-5.54 5.82-8.99V15.33c0-3.46-1.67-7.13-5.82-9");
}

</style>
