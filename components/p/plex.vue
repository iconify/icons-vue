<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xxdvmkadk"><path class="xr2zbcccf"/><path clip-rule="evenodd" class="iap14e4fj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:plex" /></template>
<style>
.iap14e4fj {
  fill-rule: evenodd;
  d: path("M20.993 10.523v3.232c0 3.83-3.758 7.244-11.26 7.244C7.582 21 3 20.015 3 13.468v-3.223c0-6.575 8.993-7.244 11.26-7.244c7.085 0 6.75 7.15 6.733 7.522m-5.056-.042c0-2.193-1.165-3.543-2.824-3.543c-1.106 0-3.13.808-4.222 1.244l-.266.106v8.774h2.25v-3.285q.19.071.374.15c.384.161.768.323 1.313.323c1.828 0 3.375-1.57 3.375-3.769");
}

.xr2zbcccf {
  d: path("M10.875 12.561V8.624h1.124c1.165 0 1.688.45 1.688 1.969c0 1.214-.692 1.968-1.688 1.968z");
}

.xxdvmkadk {
  fill: var(--svg-color--f08296, #f08296);
}

</style>
