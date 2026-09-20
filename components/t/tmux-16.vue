<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe_46l15z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oe_46l15z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:tmux-16" /></template>
