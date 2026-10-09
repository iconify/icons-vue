<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvz2snqgx.css';
import '../../css/g/gulcoab9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pvz2snqgx"/><path class="gulcoab9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sand-battery-20" /></template>
