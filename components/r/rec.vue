<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx40fmwto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-4};
const content = `<path class="jx40fmwto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:rec" /></template>
