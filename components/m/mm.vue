<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rd8b6f9us.css';
import '../../css/i/iwg23acuw.css';
import '../../css/m/muqve3b3v.css';
import '../../css/j/jstusf5pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rd8b6f9us"/><path class="iwg23acuw"/><path class="muqve3b3v"/><path class="jstusf5pk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:mm" /></template>
