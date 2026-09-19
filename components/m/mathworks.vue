<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8877ob4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s8877ob4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:mathworks" /></template>
