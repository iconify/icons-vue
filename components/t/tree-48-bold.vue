<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br_hr0bcl.css';
import '../../css/g/gka_evgvf.css';
import '../../css/g/gw1hyez2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="br_hr0bcl"/><path class="gka_evgvf"/><path class="gw1hyez2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tree-48-bold" /></template>
