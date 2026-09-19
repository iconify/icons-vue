<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwnuy0bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwnuy0bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:unhealthy-food-24px" /></template>
