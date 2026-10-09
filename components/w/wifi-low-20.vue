<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vupwwln_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vupwwln_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-low-20" /></template>
