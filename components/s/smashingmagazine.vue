<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7avee-fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u7avee-fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:smashingmagazine" /></template>
