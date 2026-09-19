<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it3rg1bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="it3rg1bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ruble-sign" /></template>
