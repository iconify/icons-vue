<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3320-d5h.css';
import '../../css/m/mt6c1q4zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z3320-d5h"/><path class="mt6c1q4zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pen-sparkle-20" /></template>
