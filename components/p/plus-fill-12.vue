<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhbw-h_zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rhbw-h_zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plus-fill-12" /></template>
