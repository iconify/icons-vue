<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op02w5bbu.css';
import '../../css/s/s6hyw202b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="op02w5bbu"/><path class="s6hyw202b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:redo-20" /></template>
