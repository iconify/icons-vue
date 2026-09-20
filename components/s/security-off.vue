<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5xdmn.css';
import '../../css/i/i8l_mw.css';
import '../../css/o/oxx-om.css';
import '../../css/t/t-ne3j.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/s/so-from-60.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGKkoblHIK"><path class="c5xdmn i8l_mw"/><path class="c5xdmn oxx-om t-ne3j"/></mask></defs><path mask="url(#SVGKkoblHIK)" class="botfzx"/><path class="c5xdmn gd_4-q t-ne3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:security-off" /></template>
