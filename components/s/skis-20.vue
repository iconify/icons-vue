<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apm4u9oep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="apm4u9oep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skis-20" /></template>
