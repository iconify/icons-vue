<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxpwcyb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rxpwcyb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:warning" /></template>
