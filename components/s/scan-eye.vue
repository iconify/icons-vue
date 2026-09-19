<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/k7rysmbfb.css';
import '../../css/o/ot72cwhlb.css';
import '../../css/z/z7n6qibgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k7rysmbfb"/><circle class="ot72cwhlb"/><path class="z7n6qibgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:scan-eye" /></template>
