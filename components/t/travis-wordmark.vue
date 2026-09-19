<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqgc4ybaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iqgc4ybaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:travis-wordmark" /></template>
