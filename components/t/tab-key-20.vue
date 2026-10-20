<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grwem7bvz.css';
import '../../css/a/anr4_-b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="grwem7bvz"/><path class="anr4_-b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tab-key-20" /></template>
