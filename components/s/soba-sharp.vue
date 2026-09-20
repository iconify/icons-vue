<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycp6nwc4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:soba-sharp" /></template>
<style>
.ycp6nwc4d {
  fill: currentColor;
  d: path("m4.187 21l-1.168-4.615h1.398q.05-.533.202-1.027T5 14.413V4.75L21 3v.904L10.423 5.069v2.104H21v.885H10.423v2.202q.389-.07.786-.117t.81-.047q2.89 0 5.06 1.783t2.536 4.506H21L19.821 21zm1.254-4.615h2.388q.344-1.37 1.512-2.243q1.167-.873 2.678-.873t2.667.873t1.499 2.242h2.388q-.362-2.296-2.226-3.792t-4.328-1.496q-2.488 0-4.353 1.496T5.44 16.384m3.508 0h6.136q-.309-.936-1.15-1.525q-.842-.59-1.915-.59t-1.917.59t-1.154 1.525m-3.064-3.397q.302-.39.649-.718q.346-.327.736-.61v-3.6H5.884zm2.27-1.91q.327-.183.67-.324t.715-.26V8.057H8.153zm-2.27-3.904H7.27v-1.77l-1.384.159zm2.27 0h1.385V5.162l-1.385.144z");
}

</style>
