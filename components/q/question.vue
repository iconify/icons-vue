<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9t0j1b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":928,"height":1280};
const content = `<path class="s9t0j1b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:question" /></template>
