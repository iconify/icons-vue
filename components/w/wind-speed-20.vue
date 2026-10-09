<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trmttkbvo.css';
import '../../css/h/hire59f7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="trmttkbvo"/><path class="hire59f7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-speed-20" /></template>
