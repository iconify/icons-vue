<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky_ty42kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":16};
const content = `<path class="ky_ty42kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:menu2" /></template>
