<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic_-zr8ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ic_-zr8ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:openapi-wordmark" /></template>
