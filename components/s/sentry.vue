<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig7v8bb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ig7v8bb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sentry" /></template>
