<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om_2m0e4d.css';
import '../../css/b/bg9q4obqt.css';
import '../../css/s/see0y-btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="om_2m0e4d"/><path class="bg9q4obqt"/><path class="see0y-btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monitor-48-bold" /></template>
