<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/r/rhi_p7bme.css';
import '../../css/l/lq43vqaom.css';
import '../../css/b/b88eryboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="rhi_p7bme"/><path class="lq43vqaom"/><circle class="b88eryboh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:people-multiple" /></template>
