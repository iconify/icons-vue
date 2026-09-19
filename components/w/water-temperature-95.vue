<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5r4nqb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="l5r4nqb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:water-temperature-95" /></template>
