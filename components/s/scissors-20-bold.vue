<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp1m28b3m.css';
import '../../css/c/cm9yy8b4y.css';
import '../../css/w/wbx0tpvjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tp1m28b3m"/><path class="cm9yy8b4y"/><path class="wbx0tpvjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scissors-20-bold" /></template>
