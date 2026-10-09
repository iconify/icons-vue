<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up8_hjm1g.css';
import '../../css/k/k_6prvftm.css';
import '../../css/q/qljqqy97f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="up8_hjm1g"/><path class="k_6prvftm"/><path class="qljqqy97f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:whisk-48" /></template>
