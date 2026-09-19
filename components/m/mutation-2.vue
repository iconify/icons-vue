<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/f6rrh3byv.css';
import '../../css/q/qfiyzsrnv.css';
import '../../css/v/vhiyc9brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6rrh3byv"/><path class="qfiyzsrnv"/><path class="vhiyc9brz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:mutation-2" /></template>
