<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsx9bkbtz.css';
import '../../css/g/gq2n7-bry.css';
import '../../css/m/munnn-b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jsx9bkbtz"/><path class="gq2n7-bry"/><path class="munnn-b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:zoom-in-20" /></template>
