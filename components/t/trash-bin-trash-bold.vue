<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dn68vbb_a.css';
import '../../css/s/sv3zhyagg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dn68vbb_a"/><path clip-rule="evenodd" class="sv3zhyagg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:trash-bin-trash-bold" /></template>
