<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkij9-1rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tkij9-1rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:power-pole" /></template>
