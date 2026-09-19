<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht2k5ha8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ht2k5ha8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:reload-fill-12" /></template>
