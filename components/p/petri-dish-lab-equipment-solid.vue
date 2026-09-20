<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-v2uebtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-v2uebtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:petri-dish-lab-equipment-solid" /></template>
