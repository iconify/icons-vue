<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it8r15bsj.css';
import '../../css/r/rk4fbbbyc.css';
import '../../css/p/pneyzwbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="it8r15bsj"/><path class="rk4fbbbyc"/><path class="pneyzwbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paint-roller-20-bold" /></template>
