<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa-e4t9pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa-e4t9pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:utensils" /></template>
