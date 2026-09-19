<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp9a7dbdx.css';
import '../../css/d/dcr78hbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gp9a7dbdx"/><path class="dcr78hbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:radio-combat" /></template>
