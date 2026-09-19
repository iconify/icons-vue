<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub-8xvdrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub-8xvdrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:objects-column-outline" /></template>
