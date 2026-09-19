<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jus8-bbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jus8-bbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:music" /></template>
