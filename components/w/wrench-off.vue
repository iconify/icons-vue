<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb1lvnu1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb1lvnu1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:wrench-off" /></template>
