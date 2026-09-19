<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvbaz-blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="uvbaz-blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:water-temperature-60" /></template>
