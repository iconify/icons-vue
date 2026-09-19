<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e95yi8b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="e95yi8b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:step-forward" /></template>
