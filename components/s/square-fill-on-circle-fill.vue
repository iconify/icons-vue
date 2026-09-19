<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf4_o-boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="sf4_o-boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-fill-on-circle-fill" /></template>
