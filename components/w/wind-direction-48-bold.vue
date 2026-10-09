<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqep3ob2t.css';
import '../../css/p/p9q9isb-a.css';
import '../../css/r/rk00lts6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fqep3ob2t"/><path class="p9q9isb-a"/><path class="rk00lts6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-direction-48-bold" /></template>
