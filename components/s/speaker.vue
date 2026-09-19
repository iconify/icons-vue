<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/n/nh7mpvbel.css';
import '../../css/m/mh0xd-bff.css';
import '../../css/s/sxgl_euno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="nh7mpvbel"/><path class="mh0xd-bff"/><path class="sxgl_euno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:speaker" /></template>
