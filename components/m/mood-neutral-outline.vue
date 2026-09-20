<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_d7vcznv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o_d7vcznv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:mood-neutral-outline" /></template>
