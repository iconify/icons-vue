<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxen2xbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxen2xbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:novu" /></template>
