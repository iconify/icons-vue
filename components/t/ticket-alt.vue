<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq6h8d1ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq6h8d1ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:ticket-alt" /></template>
