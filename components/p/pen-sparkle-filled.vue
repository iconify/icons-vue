<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/twpulwdgq.css';
import '../../css/g/gao_k8b0n.css';
import '../../css/c/cd5gr7bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="twpulwdgq"/><circle class="gao_k8b0n"/><path class="cd5gr7bnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pen-sparkle-filled" /></template>
