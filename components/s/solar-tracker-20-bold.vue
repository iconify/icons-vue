<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al_ly38km.css';
import '../../css/u/uav-pacbt.css';
import '../../css/a/ag99qbbai.css';
import '../../css/l/l7namiv5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="al_ly38km"/><path class="uav-pacbt"/><path class="ag99qbbai"/><path class="l7namiv5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-tracker-20-bold" /></template>
