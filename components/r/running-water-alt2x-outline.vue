<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuun46b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fuun46b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:running-water-alt2x-outline" /></template>
