<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8347h8je.css';
import '../../css/n/n4wo8ebep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f8347h8je"/><path class="n4wo8ebep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:winch-20-bold" /></template>
