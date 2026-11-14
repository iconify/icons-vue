<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufs6qdcmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:neighbourhood-watch" /></template>
<style>
.ufs6qdcmt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.004 10.438l8.5-7.5q.051-.045.109-.08t.122-.06t.13-.036T12 2.75t.135.012t.13.036q.064.025.122.06t.109.08l8.5 7.5q.121.106.188.254q.066.147.066.308v8q0 2.25-2.25 2.25H5q-2.25 0-2.25-2.25v-8q0-.161.066-.308q.067-.148.188-.254M12 11q-3.312 0-5.6 3.05q-.036.048-.064.102t-.048.111t-.028.117q-.01.06-.01.12t.01.12t.028.117q.02.058.048.111q.028.054.064.102Q8.688 18 12 18q3.313 0 5.6-3.05q.036-.048.064-.102t.048-.111q.019-.057.028-.117t.01-.12q0-.06-.01-.12q-.009-.06-.028-.117t-.048-.111q-.028-.054-.064-.102Q15.313 11 12 11");
}

</style>
