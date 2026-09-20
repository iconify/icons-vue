<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/vny47hble.css';
import '../../css/b/brc86cc0s.css';
import '../../css/e/epa2j5v2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vny47hble"/><path class="brc86cc0s"/><path class="epa2j5v2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:repeat-one-broken" /></template>
