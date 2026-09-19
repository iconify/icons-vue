<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppbonk68x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppbonk68x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:xbox-x" /></template>
