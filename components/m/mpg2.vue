<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8y-0xb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g8y-0xb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mpg2" /></template>
