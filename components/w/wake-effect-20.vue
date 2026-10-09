<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgz8hfjwl.css';
import '../../css/f/f55k4bcmg.css';
import '../../css/m/ma4byl76i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pgz8hfjwl"/><path class="f55k4bcmg"/><path class="ma4byl76i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wake-effect-20" /></template>
