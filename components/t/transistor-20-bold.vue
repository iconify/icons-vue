<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6lsc2brm.css';
import '../../css/u/uykl-2-4c.css';
import '../../css/m/mlich4fig.css';
import '../../css/n/ntp17abmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o6lsc2brm"/><path class="uykl-2-4c"/><path class="mlich4fig"/><path class="ntp17abmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transistor-20-bold" /></template>
