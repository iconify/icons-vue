<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bt4xg4ftq.css';
import '../../css/t/tlx_fcsoo.css';
import '../../css/v/v08vece2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bt4xg4ftq"/><path class="tlx_fcsoo"/><path class="v08vece2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wallet-add-01" /></template>
