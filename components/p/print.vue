<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5ds6_93y.css';
import '../../css/f/fkgg8p-2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5ds6_93y"/><path class="fkgg8p-2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:print" /></template>
