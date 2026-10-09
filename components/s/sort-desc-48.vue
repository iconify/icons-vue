<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhifx_scc.css';
import '../../css/g/gyvla6x2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bhifx_scc"/><path class="gyvla6x2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sort-desc-48" /></template>
