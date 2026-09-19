<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1f7s7bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="x1f7s7bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sparkle-fill-12" /></template>
