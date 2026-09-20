<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/lybqr_27c.css';
import '../../css/b/btz76nbfi.css';
import '../../css/z/zurft_ftu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lybqr_27c"/><path class="btz76nbfi"/><path class="zurft_ftu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:refresh-2" /></template>
