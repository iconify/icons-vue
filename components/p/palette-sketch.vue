<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t78q7ssck.css';
import '../../css/a/aa1uukbal.css';
import '../../css/q/q0028p0hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t78q7ssck"/><path class="aa1uukbal wm-k"/><path class="q0028p0hj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:palette-sketch" /></template>
