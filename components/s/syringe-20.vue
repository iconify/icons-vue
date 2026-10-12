<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc5dhreuj.css';
import '../../css/o/oi73mpbyr.css';
import '../../css/q/qjjqbcoej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vc5dhreuj"/><path class="oi73mpbyr"/><path class="qjjqbcoej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:syringe-20" /></template>
