<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/bgkedx2vt.css';
import '../../css/n/n01fju59i.css';
import '../../css/i/ilf33kbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bgkedx2vt"/><path class="n01fju59i"/><path class="ilf33kbod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:timezone" /></template>
