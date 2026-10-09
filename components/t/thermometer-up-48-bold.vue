<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8kv1hbar.css';
import '../../css/g/gb_71gb0y.css';
import '../../css/y/yvuobzjdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j8kv1hbar"/><path class="gb_71gb0y"/><path class="yvuobzjdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-up-48-bold" /></template>
