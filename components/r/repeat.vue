<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/medlfouzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="medlfouzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:repeat" /></template>
