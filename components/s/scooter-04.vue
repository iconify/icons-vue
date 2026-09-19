<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/ezgrq_b8g.css';
import '../../css/o/ozw_qtvty.css';
import '../../css/l/llj5fwt9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ezgrq_b8g"/><circle class="ozw_qtvty"/><path class="llj5fwt9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:scooter-04" /></template>
