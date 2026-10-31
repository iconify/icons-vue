<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou0e18q7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou0e18q7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-chevron-down-round" /></template>
