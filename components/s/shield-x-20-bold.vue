<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdw3vx8xp.css';
import '../../css/j/jvw59ybyg.css';
import '../../css/z/ztv5co6ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fdw3vx8xp"/><path class="jvw59ybyg"/><path class="ztv5co6ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-x-20-bold" /></template>
