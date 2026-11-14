<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooal3lg3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:motorbike-dealer" /></template>
<style>
.ooal3lg3h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143Q2.75 10.154 2.75 11.711v6.164q0 3.375 3.375 3.375h11.75q3.375 0 3.375-3.375v-6.164q0-1.557-1.185-2.568L14.19 4.132q-2.19-1.866-4.38 0zm10.166 6.853l-.187-.746h-2.498l-.787 1.258q.621.686.621 1.992q0 2.75-2.75 2.75T5.75 18.5t2.75-2.75q.43 0 .792.067l1.072-1.714q.051-.081.12-.147t.152-.112t.176-.07t.188-.024h2.539l-.267-1.068q-.018-.072-.021-.146q-.004-.073.007-.146t.036-.143t.063-.133t.088-.118t.108-.099q.06-.044.127-.075q.066-.032.138-.05q.09-.022.182-.022h1.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.539l.267 1.068l.358 1.433q2.664.042 2.664 2.749q0 2.75-2.75 2.75t-2.75-2.75q0-1.927 1.351-2.504");
}

</style>
