<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enxtphbky.css';
import '../../css/n/n4d5fac5i.css';
import '../../css/u/u6c3ru_1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="enxtphbky"/><path class="n4d5fac5i"/><path class="u6c3ru_1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offshore-wind-farm-20" /></template>
