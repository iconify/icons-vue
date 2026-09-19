<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz3sp2bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jz3sp2bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:rtl" /></template>
