<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvfq3_bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvfq3_bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:probe" /></template>
