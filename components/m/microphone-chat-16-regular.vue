<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x_hyvxbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microphone-chat-16-regular" /></template>
<style>
.x_hyvxbcl {
  fill: currentColor;
  d: path("M15.5 8a.5.5 0 0 1 .5.5a4.5 4.5 0 0 1-4 4.47v1.53a.5.5 0 0 1-1 0v-1.53A4.5 4.5 0 0 1 7 8.5a.5.5 0 0 1 1 0a3.5 3.5 0 1 0 7 0a.5.5 0 0 1 .5-.5M6.502 1c1.358 0 2.6.493 3.56 1.309a3.5 3.5 0 0 0-.885.573a4.5 4.5 0 0 0-6.645 5.737c.058.11.075.237.045.358l-.482 1.926l1.924-.481a.5.5 0 0 1 .358.045A4.5 4.5 0 0 0 6.502 11l.099-.003q.262.511.62.954a5.5 5.5 0 0 1-3.138-.515l-2.149.54a.75.75 0 0 1-.91-.91l.537-2.153A5.5 5.5 0 0 1 6.502 1M11.5 3A2.5 2.5 0 0 1 14 5.5v3a2.5 2.5 0 0 1-5 0v-3A2.5 2.5 0 0 1 11.5 3m0 1A1.5 1.5 0 0 0 10 5.5v3a1.5 1.5 0 0 0 3 0v-3A1.5 1.5 0 0 0 11.5 4");
}

</style>
