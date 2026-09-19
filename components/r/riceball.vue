<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3we5pccv.css';
import '../../css/t/tli6u_ttm.css';
import '../../css/b/b7ri4q8vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z3we5pccv"/><path class="tli6u_ttm"/><path class="b7ri4q8vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:riceball" /></template>
