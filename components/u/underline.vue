<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofvi3bb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ofvi3bb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:underline" /></template>
