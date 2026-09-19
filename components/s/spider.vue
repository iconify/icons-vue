<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtrr_obsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="dtrr_obsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:spider" /></template>
