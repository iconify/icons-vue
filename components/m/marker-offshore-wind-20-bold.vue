<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hei8_htdz.css';
import '../../css/i/i8o4zccnq.css';
import '../../css/i/i7l6kd2gn.css';
import '../../css/a/avx7231xh.css';
import '../../css/f/f3cd6bcna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hei8_htdz"/><path class="i8o4zccnq"/><path class="i7l6kd2gn"/><path class="avx7231xh"/><path class="f3cd6bcna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-offshore-wind-20-bold" /></template>
