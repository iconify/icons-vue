<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kokupk2te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":512};
const content = `<path class="kokupk2te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:utensils" /></template>
