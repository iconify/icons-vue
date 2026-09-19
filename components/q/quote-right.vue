<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0827bbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="q0827bbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:quote-right" /></template>
