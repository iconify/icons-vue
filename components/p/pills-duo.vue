<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq03-8bxa.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vyobbkbhc.css';
import '../../css/f/fqclo1b7h.css';
import '../../css/w/wezarpbyl.css';
import '../../css/l/lu5kmdbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq03-8bxa secondary"/><g class="dt0cm9dhy primary"><path class="vyobbkbhc"/><path class="fqclo1b7h"/><path class="wezarpbyl"/><path class="lu5kmdbub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pills-duo" /></template>
