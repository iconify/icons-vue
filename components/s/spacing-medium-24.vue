<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8g9ogb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8g9ogb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:spacing-medium-24" /></template>
