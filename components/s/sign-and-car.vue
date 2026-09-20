<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laax27b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="laax27b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:sign-and-car" /></template>
