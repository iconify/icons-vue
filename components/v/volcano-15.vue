<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tps-tw1ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tps-tw1ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:volcano-15" /></template>
