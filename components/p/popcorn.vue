<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo_wluuda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo_wluuda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:popcorn" /></template>
