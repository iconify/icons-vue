<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ale99obtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ale99obtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:volume-slash" /></template>
