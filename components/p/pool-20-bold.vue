<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofsojfsnm.css';
import '../../css/q/q45btnm6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ofsojfsnm"/><path class="q45btnm6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pool-20-bold" /></template>
