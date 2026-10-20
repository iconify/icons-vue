<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc8ay19in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jc8ay19in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sparkle-20-bold" /></template>
