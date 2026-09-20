<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfabep-5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gfabep-5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:yen" /></template>
