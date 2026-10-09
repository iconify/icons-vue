<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hda81ubct.css';
import '../../css/o/ot3162boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hda81ubct"/><path class="ot3162boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paw-48-bold" /></template>
