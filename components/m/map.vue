<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff375zpxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="ff375zpxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:map" /></template>
