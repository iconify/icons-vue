<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8fvisblt.css';
import '../../css/t/t-o-xlbsw.css';
import '../../css/p/pyphtmbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="n8fvisblt"/><path class="t-o-xlbsw"/><path class="pyphtmbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:pencil" /></template>
