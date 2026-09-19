<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikcfa0bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ikcfa0bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pin-fill" /></template>
