<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qep74_b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="qep74_b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:picture" /></template>
