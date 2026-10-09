<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf9z-jb7h.css';
import '../../css/a/ah_0o9bzq.css';
import '../../css/j/jih-r1b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rf9z-jb7h"/><path class="ah_0o9bzq"/><path class="jih-r1b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-panel-bolt-48" /></template>
