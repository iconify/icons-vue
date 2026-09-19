<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/h99d28g7n.css';
import '../../css/i/i7nhoi20w.css';
import '../../css/l/l76wbdc6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h99d28g7n"/><circle class="i7nhoi20w"/><path class="l76wbdc6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-key" /></template>
