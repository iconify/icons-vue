<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iri4s80tq.css';
import '../../css/j/jfedwfb_m.css';
import '../../css/l/lg562ex1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iri4s80tq"/><path class="jfedwfb_m"/><path class="lg562ex1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:org-unit" /></template>
