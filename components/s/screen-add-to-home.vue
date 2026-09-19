<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/x/xm3as_bdr.css';
import '../../css/g/gokw35m3p.css';
import '../../css/r/re9a3j93t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xm3as_bdr"/><path class="gokw35m3p"/><path class="re9a3j93t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:screen-add-to-home" /></template>
