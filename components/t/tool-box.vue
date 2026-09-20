<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh8istksq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh8istksq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:tool-box" /></template>
