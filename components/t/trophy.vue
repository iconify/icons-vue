<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcvn6yb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="kcvn6yb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:trophy" /></template>
