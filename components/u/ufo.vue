<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8hp_8b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="w8hp_8b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:ufo" /></template>
