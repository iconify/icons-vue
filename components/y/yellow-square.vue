<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g016nwbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g016nwbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:yellow-square" /></template>
