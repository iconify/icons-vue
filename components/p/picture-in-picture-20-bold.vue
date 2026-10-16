<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-w1mof7v.css';
import '../../css/j/jbt_l8bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b-w1mof7v"/><path class="jbt_l8bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:picture-in-picture-20-bold" /></template>
