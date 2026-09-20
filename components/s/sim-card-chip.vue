<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3un0yblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="u3un0yblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:sim-card-chip" /></template>
