<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmejzn51m.css';
import '../../css/x/xc7m02d-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fmejzn51m"/><path class="ouiIcon__fillSecondary xc7m02d-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:ml-classification-job" /></template>
