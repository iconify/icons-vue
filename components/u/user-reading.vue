<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqzjg74_k.css';
import '../../css/x/xf-y1rnlx.css';
import '../../css/i/is60ubtfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="lqzjg74_k"/><path class="xf-y1rnlx"/><path clip-rule="evenodd" class="is60ubtfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-reading" /></template>
