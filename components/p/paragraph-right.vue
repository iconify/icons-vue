<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epwa4ib1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="epwa4ib1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:paragraph-right" /></template>
