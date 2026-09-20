<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eyh5gf8py.css';
import '../../css/k/ke227gbwo.css';
import '../../css/k/k9825nbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eyh5gf8py"/><path class="ke227gbwo"/><path clip-rule="evenodd" class="k9825nbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:programming-outline" /></template>
