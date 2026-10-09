<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilg_98b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ilg_98b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:minus-48-bold" /></template>
