<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjz_80bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pjz_80bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:user" /></template>
