<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea8f0gb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea8f0gb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:smoothcomp" /></template>
