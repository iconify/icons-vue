<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njrf_nrvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="njrf_nrvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:telephone" /></template>
