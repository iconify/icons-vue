<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa2v1ywbh.css';
import '../../css/r/rfg83443v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sa2v1ywbh"/><path class="rfg83443v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-plus-20" /></template>
