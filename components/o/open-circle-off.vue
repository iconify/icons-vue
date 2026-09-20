<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cbvjzsq1u.css';
import '../../css/h/hdc_1zb4r.css';
import '../../css/u/u7b6urb1h.css';
import '../../css/p/ps4nekbve.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="cbvjzsq1u"/><path class="hdc_1zb4r"/><path class="u7b6urb1h"/><path class="ps4nekbve"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:open-circle-off" /></template>
