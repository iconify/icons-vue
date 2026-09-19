<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smn904b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="smn904b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:subdirectory" /></template>
