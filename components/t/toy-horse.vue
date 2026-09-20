<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipb_7ybiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ipb_7ybiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:toy-horse" /></template>
