<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4oci9b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s4oci9b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:palette-fill" /></template>
