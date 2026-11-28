<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd9sr7hhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd9sr7hhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:soda-can" /></template>
