<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnea9oquu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dnea9oquu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:process-line" /></template>
