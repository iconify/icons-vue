<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fabazvbbq.css';
import '../../css/c/c8jp6n-8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fabazvbbq"/><path class="c8jp6n-8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:towels-20" /></template>
