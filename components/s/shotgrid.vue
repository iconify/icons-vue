<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otlbybqix.css';
import '../../css/n/nbsc69_8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="otlbybqix"/><path class="nbsc69_8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:shotgrid" /></template>
