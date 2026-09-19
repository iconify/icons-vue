<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqwedw9qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iqwedw9qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:utk" /></template>
