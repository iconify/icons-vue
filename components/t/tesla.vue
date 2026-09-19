<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkb4orbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wkb4orbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:tesla" /></template>
