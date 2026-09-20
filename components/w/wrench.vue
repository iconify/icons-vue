<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfu6s6g3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lfu6s6g3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:wrench" /></template>
