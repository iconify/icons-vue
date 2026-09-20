<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ony_qh-1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ony_qh-1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:timer" /></template>
