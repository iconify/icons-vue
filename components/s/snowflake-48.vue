<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcailpd3t.css';
import '../../css/k/k_y542bvu.css';
import '../../css/c/clrbi72ou.css';
import '../../css/o/o1-his81l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dcailpd3t"/><path class="k_y542bvu"/><path class="clrbi72ou"/><path class="o1-his81l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:snowflake-48" /></template>
