<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myl2x9bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="myl2x9bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:receipt-refund" /></template>
