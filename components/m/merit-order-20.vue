<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km2fl-ght.css';
import '../../css/v/vurhcwkho.css';
import '../../css/r/rkgzl8y0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="km2fl-ght"/><path class="vurhcwkho"/><path class="rkgzl8y0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:merit-order-20" /></template>
