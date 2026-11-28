<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc_3m-lqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc_3m-lqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:screen-share-x" /></template>
