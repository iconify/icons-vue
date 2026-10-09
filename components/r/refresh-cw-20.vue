<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlf63wklu.css';
import '../../css/c/clfrelb4k.css';
import '../../css/h/hs6jekbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jlf63wklu"/><path class="clfrelb4k"/><path class="hs6jekbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refresh-cw-20" /></template>
