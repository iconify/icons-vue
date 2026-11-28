<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9sf489xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9sf489xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:radio-button" /></template>
