<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiz7ntixz.css';
import '../../css/p/pds76bc9q.css';
import '../../css/o/ov285yggp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hiz7ntixz"/><path class="pds76bc9q"/><path class="ov285yggp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:park-and-ride-20-bold" /></template>
