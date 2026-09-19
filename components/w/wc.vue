<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9-1_7jmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9-1_7jmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:wc" /></template>
