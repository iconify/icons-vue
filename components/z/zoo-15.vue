<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_9mhsbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h_9mhsbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:zoo-15" /></template>
