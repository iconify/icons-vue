<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfjvhv-9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfjvhv-9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scissors-fill" /></template>
