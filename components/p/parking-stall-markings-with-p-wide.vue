<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0wz6zwkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m0wz6zwkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:parking-stall-markings-with-p-wide" /></template>
