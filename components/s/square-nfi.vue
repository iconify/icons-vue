<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g27f8y-km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g27f8y-km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:square-nfi" /></template>
