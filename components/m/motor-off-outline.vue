<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2qisrbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2qisrbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:motor-off-outline" /></template>
