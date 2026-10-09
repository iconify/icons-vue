<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibs8b-b6s.css';
import '../../css/r/rh7lscyqa.css';
import '../../css/y/y6m516bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ibs8b-b6s"/><path class="rh7lscyqa"/><path class="y6m516bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wireless-charging-48-bold" /></template>
