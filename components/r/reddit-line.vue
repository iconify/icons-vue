<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7hi9sbth.css';
import '../../css/u/ukauanbdu.css';
import '../../css/m/mrpd8lbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7hi9sbth"/><path class="ukauanbdu"/><path class="mrpd8lbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:reddit-line" /></template>
