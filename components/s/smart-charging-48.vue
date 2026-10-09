<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzvl6-gkr.css';
import '../../css/x/x-s9mn_cg.css';
import '../../css/r/r83jtnbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nzvl6-gkr"/><path class="x-s9mn_cg"/><path class="r83jtnbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-charging-48" /></template>
