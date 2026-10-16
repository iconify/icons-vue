<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7o4albhq.css';
import '../../css/z/z70t_abxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z7o4albhq"/><path class="z70t_abxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:seabed-survey-20" /></template>
