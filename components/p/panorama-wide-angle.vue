<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi_in7rna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="fi_in7rna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:panorama-wide-angle" /></template>
