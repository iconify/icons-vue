<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg_h37b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg_h37b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smartphone-question" /></template>
