<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG7z9QOb6u)" class="web96eblq"/><path fill="url(#SVGjhrkydAU)" class="vm3v4tvqn"/><defs><linearGradient id="SVG7z9QOb6u" x1="19.2" x2="3.011" y1="3.473" y2="19.211" gradientUnits="userSpaceOnUse"><stop class="u306osbex"/><stop offset="1" class="l-jphgqml"/></linearGradient><linearGradient id="SVGjhrkydAU" x1="12.006" x2="5.481" y1="3" y2="12.45" gradientUnits="userSpaceOnUse"><stop class="t35ahednt"/><stop offset="1" class="ucxuiibhr"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trvl" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l-jphgqml {
  stop-color: var(--svg-color--c1d0d1, #c1d0d1);
}

.t35ahednt {
  stop-color: var(--svg-color--c7d5d6, #c7d5d6);
}

.u306osbex {
  stop-color: var(--svg-color--8fa3a4, #8fa3a4);
}

.ucxuiibhr {
  stop-color: var(--svg-color--5a6966, #5a6966);
}

.vm3v4tvqn {
  d: path("M6.375 9.187c2.2 0 3.91 1.345 4.866 2.121a.05.05 0 0 0 .033.015a.05.05 0 0 0 .034-.015a.045.045 0 0 0 0-.062c-.776-.956-2.126-2.666-2.126-4.871C9.182 3 11.719 3 12 3v9H3c0-.281 0-2.813 3.375-2.813");
}

.web96eblq {
  d: path("M21 12c0 .563-.281 2.824-3.38 2.824c-2.2 0-3.916-1.35-4.866-2.12a.045.045 0 0 0-.057 0a.045.045 0 0 0-.01.061c.776.956 2.126 2.65 2.126 4.86C14.813 19.228 12.675 21 12 21v-9z");
}

</style>
