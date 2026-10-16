<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agj07mbsi.css';
import '../../css/d/dmuhyjbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="agj07mbsi"/><path class="dmuhyjbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phase-shifter-48-bold" /></template>
