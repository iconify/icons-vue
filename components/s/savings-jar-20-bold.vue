<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtdrk6b1n.css';
import '../../css/m/moe3g5b7s.css';
import '../../css/h/hvh37gb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mtdrk6b1n"/><path class="moe3g5b7s"/><path class="hvh37gb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:savings-jar-20-bold" /></template>
