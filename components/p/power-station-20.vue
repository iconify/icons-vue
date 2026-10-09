<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsoei1ajq.css';
import '../../css/w/waz_2hbmd.css';
import '../../css/w/wgvzgybih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tsoei1ajq"/><path class="waz_2hbmd"/><path class="wgvzgybih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-station-20" /></template>
