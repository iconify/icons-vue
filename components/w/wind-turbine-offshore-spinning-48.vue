<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w30mb-bsx.css';
import '../../css/x/xoi6f6nox.css';
import '../../css/p/poe4r5-le.css';
import '../../css/e/ekwadbbdy.css';
import '../../css/l/luqa3jbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w30mb-bsx"/><path class="xoi6f6nox"/><path class="poe4r5-le"/><path class="ekwadbbdy"/><path class="luqa3jbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-turbine-offshore-spinning-48" /></template>
