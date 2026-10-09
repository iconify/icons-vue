<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8g7dpcvt.css';
import '../../css/b/bc7iqrblt.css';
import '../../css/r/ricrltbdm.css';
import '../../css/s/smd4b0njc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u8g7dpcvt"/><path class="bc7iqrblt"/><path class="ricrltbdm"/><path class="smd4b0njc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vehicle-to-home-48" /></template>
