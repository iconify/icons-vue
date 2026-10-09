<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cau1vhb9o.css';
import '../../css/l/lm7opbs2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cau1vhb9o"/><path class="lm7opbs2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mouse-48-bold" /></template>
