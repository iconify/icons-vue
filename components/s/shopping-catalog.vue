<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsr7ujquy.css';
import '../../css/b/b42j7_b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rsr7ujquy"/><path class="b42j7_b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:shopping-catalog" /></template>
