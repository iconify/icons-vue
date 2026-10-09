<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8nww4mnw.css';
import '../../css/r/rmh-uhtym.css';
import '../../css/a/aqj0--bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n8nww4mnw"/><path class="rmh-uhtym"/><path class="aqj0--bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-plus-20" /></template>
