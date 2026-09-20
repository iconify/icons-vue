<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt6vhkb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="kt6vhkb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-spiral-stairs-down" /></template>
