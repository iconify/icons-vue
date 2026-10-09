<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkh_084xi.css';
import '../../css/w/wpnm42b6c.css';
import '../../css/g/g17jsq6yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rkh_084xi"/><path class="wpnm42b6c"/><path class="g17jsq6yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-charging-20-bold" /></template>
