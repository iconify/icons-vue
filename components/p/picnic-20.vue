<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aizeie9_j.css';
import '../../css/d/d-a358n2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aizeie9_j"/><path class="d-a358n2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:picnic-20" /></template>
