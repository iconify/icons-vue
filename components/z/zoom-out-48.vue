<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkje3ybpz.css';
import '../../css/d/d34fk4x7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gkje3ybpz"/><path class="d34fk4x7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:zoom-out-48" /></template>
