<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo734ib2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo734ib2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:task-filled" /></template>
