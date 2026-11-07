<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fly9otqib.css';
import '../../css/g/ggztb9bes.css';
import '../../css/k/k_gu13b6s.css';
import '../../css/q/qv07b1bbr.css';
import '../../css/o/ol11kpbfc.css';
import '../../css/g/gcctpwkja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fly9otqib"/><path clip-rule="evenodd" class="ggztb9bes"/><path class="k_gu13b6s"/><path class="qv07b1bbr"/><path class="ol11kpbfc"/><path class="gcctpwkja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-columns-split-outline" /></template>
