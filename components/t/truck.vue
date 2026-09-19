<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en3yd4b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1408};
const content = `<path class="en3yd4b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:truck" /></template>
