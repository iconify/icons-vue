<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryht7gr-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ryht7gr-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:pause" /></template>
