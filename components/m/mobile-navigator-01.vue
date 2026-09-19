<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/cld7pcy1f.css';
import '../../css/t/tq8y5-b6c.css';
import '../../css/w/wm1nw_8cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cld7pcy1f"/><path class="tq8y5-b6c"/><path class="wm1nw_8cg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mobile-navigator-01" /></template>
