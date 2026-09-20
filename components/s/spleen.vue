<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soxfhjvzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="soxfhjvzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spleen" /></template>
