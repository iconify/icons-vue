<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocp-zwjse.css';
import '../../css/z/znuj7bbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ocp-zwjse"/><path class="znuj7bbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-arrow-left-stroke-20" /></template>
