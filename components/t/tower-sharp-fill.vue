<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m_92v0b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tower-sharp-fill" /></template>
<style>
.m_92v0b2o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.613 1.03C11.868 0.98 12.332 0.99 12.556 1.14L21.528 7.15C21.894 7.39 22.056 7.85 21.929 8.27C21.816 8.64 21.422 8.92 21.051 8.98L19 8.98V21H23V23H1V21H5V8.98H3C2.615 8.98 2.233 8.69 2.066 8.35C1.941 7.93 2.08 7.39 2.445 7.15L11.613 1.03ZM12 10.98C10.343 10.98 9 12.33 9 13.99V18.05C9.055 18.55 9.485 19 10 19H14C14.552 19 14.999 18.55 15 17.99V13.99C15 12.33 13.657 10.98 12 10.98Z");
}

</style>
