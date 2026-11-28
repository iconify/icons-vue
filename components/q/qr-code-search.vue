<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgrv5ryss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgrv5ryss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:qr-code-search" /></template>
