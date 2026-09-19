<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt1o8pbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vt1o8pbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-3-offgrid" /></template>
