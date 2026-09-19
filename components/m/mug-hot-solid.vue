<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k_u5kmwwg.css';
import '../../css/v/vuttg4saf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k_u5kmwwg"/><path clip-rule="evenodd" class="vuttg4saf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:mug-hot-solid" /></template>
