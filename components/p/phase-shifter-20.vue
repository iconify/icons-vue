<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riu484b2u.css';
import '../../css/j/jbawidbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="riu484b2u"/><path class="jbawidbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phase-shifter-20" /></template>
