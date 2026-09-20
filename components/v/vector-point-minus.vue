<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o19s5kgey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o19s5kgey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-point-minus" /></template>
