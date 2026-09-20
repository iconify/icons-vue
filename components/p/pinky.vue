<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-3n-tfew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-3n-tfew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pinky" /></template>
