<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr5dvv4wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jr5dvv4wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-bell" /></template>
