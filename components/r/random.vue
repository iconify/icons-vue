<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9f-_9bvl.css';
import '../../css/x/x0ujedc_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<path class="r9f-_9bvl"/><path class="x0ujedc_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:random" /></template>
