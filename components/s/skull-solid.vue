<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bymhd4bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bymhd4bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:skull-solid" /></template>
