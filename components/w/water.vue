<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rinuwhlnp.css';
import '../../css/b/bmfy1bdgs.css';
import '../../css/e/ei8tu2b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="rinuwhlnp"><path class="bmfy1bdgs"/><path class="ei8tu2b9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:water" /></template>
