<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq_pa800o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq_pa800o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:star-half-stroke-outline" /></template>
