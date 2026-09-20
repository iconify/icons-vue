<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q30fo1bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q30fo1bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mask3-filled" /></template>
