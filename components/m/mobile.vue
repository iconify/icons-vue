<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5tpnz--a.css';
import '../../css/q/qn50x0b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5tpnz--a"/><path class="qn50x0b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:mobile" /></template>
