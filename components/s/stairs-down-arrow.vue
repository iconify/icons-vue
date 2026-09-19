<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxzzg3bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxzzg3bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:stairs-down-arrow" /></template>
