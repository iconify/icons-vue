<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvhip5cnc.css';
import '../../css/e/e604b0bcg.css';
import '../../css/v/v6urtjbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kvhip5cnc"/><path class="e604b0bcg"/><path class="v6urtjbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:recloser-20" /></template>
