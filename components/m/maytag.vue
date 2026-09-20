<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo0sf5qbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo0sf5qbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:maytag" /></template>
