<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl35fttde.css';
import '../../css/f/frr8tzpij.css';
import '../../css/m/mept65bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="yl35fttde"/><path class="frr8tzpij"/><path class="mept65bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:webhook-tester" /></template>
