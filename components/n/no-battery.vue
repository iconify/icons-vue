<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2z-5fbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2z-5fbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:no-battery" /></template>
