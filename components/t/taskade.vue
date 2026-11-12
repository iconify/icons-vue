<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz934u5vg.css';
import '../../css/n/ny4gz8bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pz934u5vg"/><path class="ny4gz8bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:taskade" /></template>
