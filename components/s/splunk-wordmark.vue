<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh2bigb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rh2bigb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:splunk-wordmark" /></template>
