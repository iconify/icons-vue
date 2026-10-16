<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9wztb3tr.css';
import '../../css/d/d3xoy3b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v9wztb3tr"/><path class="d3xoy3b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vr-headset-20-bold" /></template>
