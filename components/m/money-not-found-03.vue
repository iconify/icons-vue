<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/b_pl27b6t.css';
import '../../css/z/ziild8bri.css';
import '../../css/t/t4ido_b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b_pl27b6t"/><path class="ziild8bri"/><path class="t4ido_b4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-not-found-03" /></template>
