<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zys8fokom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zys8fokom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:memory" /></template>
