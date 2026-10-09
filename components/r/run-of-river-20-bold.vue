<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_i3djllq.css';
import '../../css/p/p8remmbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s_i3djllq"/><path class="p8remmbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:run-of-river-20-bold" /></template>
