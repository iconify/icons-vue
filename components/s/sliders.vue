<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahb2qab2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ahb2qab2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:sliders" /></template>
