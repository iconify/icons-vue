<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/s72l8dw0c.css';
import '../../css/z/zv6cqnbnp.css';
import '../../css/i/ii4tpe1es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s72l8dw0c"/><circle class="zv6cqnbnp"/><path class="ii4tpe1es"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:map-pin-plus" /></template>
