<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb76bo8sb.css';
import '../../css/w/wvlg02bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cb76bo8sb"/><path class="wvlg02bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:xx-1x1" /></template>
