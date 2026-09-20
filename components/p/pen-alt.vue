<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpv-cabhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lpv-cabhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pen-alt" /></template>
