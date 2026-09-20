<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcmvy2ouf.css';
import '../../css/r/rxbeq-blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lcmvy2ouf"/><path class="rxbeq-blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:networkx" /></template>
