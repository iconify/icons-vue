<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhx6kd09d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lhx6kd09d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:transit-vehicle-with-destination-display-and-pantograph-on-tram-track" /></template>
