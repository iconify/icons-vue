<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-nrxac0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e-nrxac0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:racetrack-cycling" /></template>
