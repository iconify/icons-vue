<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/chlsrtpkl.css';
import '../../css/n/nhushpb-h.css';
import '../../css/a/acuehpb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="chlsrtpkl"/><path clip-rule="evenodd" class="nhushpb-h"/><path class="acuehpb-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-speak2" /></template>
