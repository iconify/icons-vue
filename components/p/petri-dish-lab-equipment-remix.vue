<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zibuxdi7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zibuxdi7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:petri-dish-lab-equipment-remix" /></template>
