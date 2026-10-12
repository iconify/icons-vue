<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdp7o9mju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jdp7o9mju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:monitor-fill-20" /></template>
