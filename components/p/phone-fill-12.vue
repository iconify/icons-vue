<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxbikpuly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uxbikpuly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-fill-12" /></template>
