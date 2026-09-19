<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl7jbz5fr.css';
import '../../css/h/h_3i35b7d.css';
import '../../css/y/y-dj3mnsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="gl7jbz5fr"/><path class="h_3i35b7d"/><path class="y-dj3mnsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:virtual-column-key" /></template>
