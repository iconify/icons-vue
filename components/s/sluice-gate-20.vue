<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajach0a3z.css';
import '../../css/f/fyvg948cl.css';
import '../../css/x/xpigs6blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ajach0a3z"/><path class="fyvg948cl"/><path class="xpigs6blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sluice-gate-20" /></template>
