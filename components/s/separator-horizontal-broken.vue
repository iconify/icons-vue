<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/gvc65tz1p.css';
import '../../css/s/skf2dub_m.css';
import '../../css/o/oyjqk5bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gvc65tz1p"/><path class="skf2dub_m"/><path class="oyjqk5bct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:separator-horizontal-broken" /></template>
