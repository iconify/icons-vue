<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u3qbuyhuv.css';
import '../../css/q/q-v0y4m1v.css';
import '../../css/z/zi9hbuqnd.css';
import '../../css/e/eqmx3ab2e.css';
import '../../css/a/a-qdj_bea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="u3qbuyhuv"/><path clip-rule="evenodd" class="q-v0y4m1v"/><path class="zi9hbuqnd"/><path clip-rule="evenodd" class="eqmx3ab2e"/><path class="a-qdj_bea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:path" /></template>
