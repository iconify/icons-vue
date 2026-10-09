<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g22-s43ip.css';
import '../../css/f/f4_61hgfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g22-s43ip"/><path class="f4_61hgfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:undo-20-bold" /></template>
