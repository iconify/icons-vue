<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5nd0vb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s5nd0vb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rows-48-bold" /></template>
