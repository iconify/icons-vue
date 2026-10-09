<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg3h39b1g.css';
import '../../css/a/ah-ntwbee.css';
import '../../css/z/zi1nuachi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eg3h39b1g"/><path class="ah-ntwbee"/><path class="zi1nuachi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-lock-48" /></template>
