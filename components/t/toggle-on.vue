<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csg1b869a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="csg1b869a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:toggle-on" /></template>
