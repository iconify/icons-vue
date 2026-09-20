<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czxuyxj8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czxuyxj8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:take-two-interactive-software" /></template>
