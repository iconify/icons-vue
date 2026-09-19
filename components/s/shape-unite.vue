<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f88l0n6ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f88l0n6ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-unite" /></template>
