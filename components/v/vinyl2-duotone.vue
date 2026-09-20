<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m3ihwemum.css';
import '../../css/u/u1d2zpbxx.css';
import '../../css/a/abo8drbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m3ihwemum"/><path class="u1d2zpbxx"/><path clip-rule="evenodd" class="abo8drbzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:vinyl2-duotone" /></template>
