<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-5t3-bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-5t3-bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pause-circle-filled" /></template>
