<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voqy8c0sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="voqy8c0sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wave-48" /></template>
