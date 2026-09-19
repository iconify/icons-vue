<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpuj-nbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tpuj-nbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-stack-3d-down-right" /></template>
