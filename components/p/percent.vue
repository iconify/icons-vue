<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t63-sob-r.css';
import '../../css/w/wib432g-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t63-sob-r"/><path class="wib432g-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:percent" /></template>
