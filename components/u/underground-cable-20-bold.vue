<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faahkei5l.css';
import '../../css/l/lfriz8pwt.css';
import '../../css/m/m-8ppixnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="faahkei5l"/><path class="lfriz8pwt"/><path class="m-8ppixnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:underground-cable-20-bold" /></template>
