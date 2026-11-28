<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt6ajr72g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt6ajr72g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:package-heart" /></template>
