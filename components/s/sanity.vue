<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf_8ixbgf.css';
import '../../css/q/qi-5iib3f.css';
import '../../css/q/qpg1j2-ne.css';
import '../../css/d/d0extn7ce.css';
import '../../css/d/dl15vsbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="rf_8ixbgf"><path class="qi-5iib3f"/><path class="qpg1j2-ne"/><path class="d0extn7ce"/><path class="dl15vsbnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sanity" /></template>
