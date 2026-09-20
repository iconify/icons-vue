<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq60ccc1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lq60ccc1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:stratovolcano" /></template>
