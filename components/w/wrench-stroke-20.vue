<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkfru2t8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hkfru2t8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wrench-stroke-20" /></template>
