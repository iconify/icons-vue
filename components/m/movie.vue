<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnbm39bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fnbm39bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:movie" /></template>
