<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyvso6b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qyvso6b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:triangle-20" /></template>
