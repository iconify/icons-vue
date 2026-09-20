<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-n6wya5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v-n6wya5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:paint-roller" /></template>
