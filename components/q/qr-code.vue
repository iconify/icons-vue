<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/jfr6wqbhu.css';
import '../../css/l/l78icwe5e.css';
import '../../css/y/yny8akbhl.css';
import '../../css/i/iyirtsbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="jfr6wqbhu"/><rect class="l78icwe5e"/><rect class="yny8akbhl"/><path class="iyirtsbsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:qr-code" /></template>
