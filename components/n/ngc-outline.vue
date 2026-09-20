<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvku5ny2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rvku5ny2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ngc-outline" /></template>
