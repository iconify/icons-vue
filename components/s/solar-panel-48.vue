<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laksrub_s.css';
import '../../css/n/n_odgsabd.css';
import '../../css/e/ejx72qubu.css';
import '../../css/n/nsnkgmbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="laksrub_s"/><path class="n_odgsabd"/><path class="ejx72qubu"/><path class="nsnkgmbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-panel-48" /></template>
