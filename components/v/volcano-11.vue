<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vukmy-a0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="vukmy-a0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:volcano-11" /></template>
