<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm03gzbnp.css';
import '../../css/t/t8f86fbfc.css';
import '../../css/m/m4styj0nb.css';
import '../../css/m/mz1do-bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="t8f86fbfc"/><path class="m4styj0nb"/><path class="mz1do-bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-cross-square-bold-duotone" /></template>
