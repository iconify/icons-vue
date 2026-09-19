<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy6r-4lmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy6r-4lmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:suzuki" /></template>
