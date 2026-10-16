<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6f2kgb8d.css';
import '../../css/z/zd03hic5e.css';
import '../../css/f/frzwfx42e.css';
import '../../css/r/rl4r9ofhj.css';
import '../../css/w/wugkd2rdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o6f2kgb8d"/><path class="zd03hic5e"/><path class="frzwfx42e"/><path class="rl4r9ofhj"/><path class="wugkd2rdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transistor-20" /></template>
