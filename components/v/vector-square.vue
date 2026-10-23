<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfj-4o4tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfj-4o4tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:vector-square" /></template>
