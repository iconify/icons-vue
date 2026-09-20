<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srmks4o_f.css';
import '../../css/h/h6on4ibgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srmks4o_f"/><path class="h6on4ibgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:train-1" /></template>
