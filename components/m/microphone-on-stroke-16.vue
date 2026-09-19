<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/h/hkwu35btw.css';
import '../../css/o/o2--xo00n.css';
import '../../css/k/kmcbvkrhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><rect class="hkwu35btw"/><path class="o2--xo00n"/></g><path class="kmcbvkrhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:microphone-on-stroke-16" /></template>
