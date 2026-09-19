<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irbe8nbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="irbe8nbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:material-request" /></template>
