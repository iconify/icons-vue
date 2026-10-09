<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hftzc6bjl.css';
import '../../css/g/gwf5562uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hftzc6bjl"/><path class="gwf5562uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-blade-48" /></template>
