<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/p8gqlabhm.css';
import '../../css/h/hb8k3n1zg.css';
import '../../css/t/t67fgabgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="p8gqlabhm"/><path class="hb8k3n1zg"/><path class="t67fgabgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:restricted-access" /></template>
