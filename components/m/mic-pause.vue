<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtmx9jbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtmx9jbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mic-pause" /></template>
