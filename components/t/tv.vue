<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnnz_hrwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1536};
const content = `<path class="rnnz_hrwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:tv" /></template>
