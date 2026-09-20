<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb4ecm.css';
import '../../css/t/t5pxry.css';
import '../../css/i/i8_pay.css';
import '../../css/o/oxx-om.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGaQN5Mdql"><path class="cb4ecm t5pxry"/><path class="i8_pay oxx-om t5pxry"/></mask></defs><path mask="url(#SVGaQN5Mdql)" class="botfzx"/><path class="gd_4-q i8_pay t5pxry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:security-off-twotone" /></template>
