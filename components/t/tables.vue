<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k202uvbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="k202uvbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:tables" /></template>
