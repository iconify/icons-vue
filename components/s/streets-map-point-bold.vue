<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9aix1bex.css';
import '../../css/h/hh1t7h7bu.css';
import '../../css/e/e-2fhubal.css';
import '../../css/n/n6lshjbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9aix1bex"/><path class="hh1t7h7bu"/><path clip-rule="evenodd" class="e-2fhubal"/><path class="n6lshjbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-map-point-bold" /></template>
