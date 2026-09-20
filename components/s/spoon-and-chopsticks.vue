<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfd9-ubvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qfd9-ubvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spoon-and-chopsticks" /></template>
