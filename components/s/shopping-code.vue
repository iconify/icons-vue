<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzo8qqbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzo8qqbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shopping-code" /></template>
