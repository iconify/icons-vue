<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fec4cjbkq.css';
import '../../css/o/ol1pcwf7g.css';
import '../../css/e/ecvl1ebjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fec4cjbkq"/><path class="ol1pcwf7g"/><path class="ecvl1ebjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:x-square-20-bold" /></template>
