<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn4ielb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mn4ielb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:smiley-fill-12" /></template>
