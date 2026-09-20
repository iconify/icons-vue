<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-qh6iddv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e-qh6iddv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:thumb-up" /></template>
