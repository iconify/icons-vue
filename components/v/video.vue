<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_px3vb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q_px3vb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:video" /></template>
