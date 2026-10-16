<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su8djsbpl.css';
import '../../css/p/p3d2yabbm.css';
import '../../css/z/zcn-sxbli.css';
import '../../css/f/f39wppbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="su8djsbpl"/><path class="p3d2yabbm"/><path class="zcn-sxbli"/><path class="f39wppbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wire-stripper-48-bold" /></template>
