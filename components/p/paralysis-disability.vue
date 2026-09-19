<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo6-b-g-q.css';
import '../../css/u/ug9pg4zkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="lo6-b-g-q"/><path class="ug9pg4zkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:paralysis-disability" /></template>
