<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riqzryb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="riqzryb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:waste-basket" /></template>
