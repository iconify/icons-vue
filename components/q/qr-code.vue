<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/b/br-cd-bbd.css';
import '../../css/q/qfbt3bcyu.css';
import '../../css/h/hfx4ozb9p.css';
import '../../css/u/ui6zico0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><rect class="br-cd-bbd"/><rect class="qfbt3bcyu"/><rect class="hfx4ozb9p"/><path class="ui6zico0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:qr-code" /></template>
