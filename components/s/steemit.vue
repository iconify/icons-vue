<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu87k4dnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vu87k4dnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:steemit" /></template>
