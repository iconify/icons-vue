<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/thgoyylzb.css';
import '../../css/y/y1bgarbnk.css';
import '../../css/s/sngcg6bqy.css';
import '../../css/t/t9nb_q56o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="thgoyylzb"/><path class="y1bgarbnk"/><path class="sngcg6bqy"/><path class="t9nb_q56o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:unlink-broken-chain-1" /></template>
