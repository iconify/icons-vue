<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5m3vuabl.css';
import '../../css/l/l0896yttc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a5m3vuabl"/><path class="l0896yttc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tide-low-20" /></template>
