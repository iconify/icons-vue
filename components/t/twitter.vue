<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pvl2anbys.css';
import '../../css/y/ydnq8obbc.css';
import '../../css/f/fx212mbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="pvl2anbys"/><rect class="ydnq8obbc"/><path class="fx212mbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="skill-icons:twitter" /></template>
