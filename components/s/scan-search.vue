<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or0cs6mcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or0cs6mcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scan-search" /></template>
