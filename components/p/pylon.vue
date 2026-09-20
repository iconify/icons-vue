<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxb8sdb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fxb8sdb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:pylon" /></template>
