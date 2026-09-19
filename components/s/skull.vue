<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h38xtl-6m.css';
import '../../css/z/z3me40b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h38xtl-6m"/><path class="z3me40b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:skull" /></template>
