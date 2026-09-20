<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhljz6o3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="lhljz6o3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:paragraph-end" /></template>
