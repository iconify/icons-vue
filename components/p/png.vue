<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ojlt7ig2q"/><path class="pzuw1cnfo"/><path clip-rule="evenodd" class="m_eayl2pg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:png" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m_eayl2pg {
  fill: var(--svg-color--ffc800, #ffc800);
  fill-rule: evenodd;
  d: path("M12 20.47a8.47 8.47 0 1 0 0-16.94a8.47 8.47 0 0 0 0 16.94m0 .53a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.ojlt7ig2q {
  fill: var(--svg-color--e1aa00, #e1aa00);
  d: path("m8.808 7.235l-.466 1.43l2.965 2.16l-2.356 1.704L6.177 10.5l1.059-3.266zm.55 0l2.378 1.731v1.525l-2.78-2.023zm-.397 5.934l-.005.022l2.78 2.022v-4.06L8.96 13.164zm.509 1.043l2.26 1.647h.006v1.964l-2.78-2.022l.519-1.588z");
}

.pzuw1cnfo {
  fill: var(--svg-color--ffc800, #ffc800);
  d: path("M15.192 7.235h1.573l1.058 3.277l-2.779 2.017l-2.34-1.71l2.954-2.144zm-2.927 1.731l2.382-1.731l.397 1.233l-2.78 2.018V8.96zm2.774 4.204l-2.769-2.012h-.005v4.055l2.78-2.022zm-2.774 2.694l2.266-1.646l.513 1.588l-2.78 2.017V15.86z");
}

</style>
