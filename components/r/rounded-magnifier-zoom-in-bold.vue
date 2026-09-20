<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fnsxu5bca.css';
import '../../css/p/pnw6itfcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fnsxu5bca"/><path clip-rule="evenodd" class="pnw6itfcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-zoom-in-bold" /></template>
