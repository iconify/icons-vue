<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onhc3xo-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="onhc3xo-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:user-add" /></template>
