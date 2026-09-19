<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv0hedcfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="pv0hedcfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:spades-card" /></template>
