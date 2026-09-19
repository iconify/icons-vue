<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7020zbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="d7020zbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:water-temperature-50" /></template>
