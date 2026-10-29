<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/khn241bad.css';
import '../../css/n/npa4rgbjd.css';
import '../../css/l/ljcz9bcpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="khn241bad"/><path class="npa4rgbjd"/><path class="ljcz9bcpj wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-pen-solid" /></template>
