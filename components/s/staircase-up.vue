<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axg6-fbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="axg6-fbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:staircase-up" /></template>
