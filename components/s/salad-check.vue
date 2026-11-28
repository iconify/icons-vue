<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e46npbbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e46npbbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:salad-check" /></template>
