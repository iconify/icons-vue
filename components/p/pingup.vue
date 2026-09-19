<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mquy8vb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mquy8vb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:pingup" /></template>
