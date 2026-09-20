<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cic9kf80k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cic9kf80k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:void-linux" /></template>
