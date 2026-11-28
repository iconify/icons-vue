<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gla-pjbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gla-pjbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:planet" /></template>
