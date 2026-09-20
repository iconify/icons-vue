<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7-m-2byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v7-m-2byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:rj" /></template>
