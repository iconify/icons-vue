<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2neunb3u.css';
import '../../css/j/j6w_1uvml.css';
import '../../css/p/plpbozbsh.css';
import '../../css/r/rycinhbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="j6w_1uvml"/><path class="plpbozbsh"/><path class="rycinhbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermostat-48-bold" /></template>
