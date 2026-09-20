<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzi8x3byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzi8x3byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-single-neutral-female" /></template>
