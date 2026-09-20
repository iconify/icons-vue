<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/okm4lpbds.css';
import '../../css/m/mio52ig2b.css';
import '../../css/x/xtsrmvj7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="okm4lpbds"/><circle class="mio52ig2b"/><circle class="xtsrmvj7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:user-round-key" /></template>
