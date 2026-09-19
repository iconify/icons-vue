<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w10-y0b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":152,"height":432};
const content = `<path class="w10-y0b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:male-alt" /></template>
