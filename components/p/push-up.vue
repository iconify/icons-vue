<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8qa1w28i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="g8qa1w28i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:push-up" /></template>
