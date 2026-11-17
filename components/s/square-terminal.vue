<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/b/b2s-rtbbj.css';
import '../../css/y/yu3no1o6h.css';
import '../../css/t/tj75_kssw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="b2s-rtbbj"/><path class="yu3no1o6h"/><path class="tj75_kssw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:square-terminal" /></template>
