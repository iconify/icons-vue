<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s87flsbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="s87flsbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:paste" /></template>
