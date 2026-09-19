<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bopi9b9jn.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/f/fxwnb7vgp.css';
import '../../css/e/ewng3_bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="bopi9b9jn"/><circle class="h_tsn8bxt"/><circle class="fxwnb7vgp"/><path class="ewng3_bdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:waypoints" /></template>
