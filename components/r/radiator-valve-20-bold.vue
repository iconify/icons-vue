<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjaxhlnkd.css';
import '../../css/v/vlwm4ybiy.css';
import '../../css/l/lpnx10b3p.css';
import '../../css/q/qho2-b78i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yjaxhlnkd"/><path class="vlwm4ybiy"/><path class="lpnx10b3p"/><path class="qho2-b78i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:radiator-valve-20-bold" /></template>
