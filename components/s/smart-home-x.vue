<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjwd8jtei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjwd8jtei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smart-home-x" /></template>
