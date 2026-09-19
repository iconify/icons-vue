<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaapcj7my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaapcj7my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:trend-up" /></template>
