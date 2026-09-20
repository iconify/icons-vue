<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1d4hcvwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="y1d4hcvwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:run" /></template>
