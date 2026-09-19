<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsel27bbh.css';
import '../../css/x/xqhescv-e.css';
import '../../css/i/im33libln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="rsel27bbh"><path class="xqhescv-e"/><path class="im33libln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:vigo" /></template>
