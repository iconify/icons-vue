<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu2_l9r9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gu2_l9r9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sort-down" /></template>
