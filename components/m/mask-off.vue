<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfp_8ibvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jfp_8ibvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:mask-off" /></template>
