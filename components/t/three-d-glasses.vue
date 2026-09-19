<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/w/w34bfwbzs.css';
import '../../css/s/s39phnkpe.css';
import '../../css/t/t5ok4fbuh.css';
import '../../css/f/fjt16qbnj.css';
import '../../css/e/eee7vnjin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="w34bfwbzs"/><path class="s39phnkpe"/><path class="t5ok4fbuh"/><path clip-rule="evenodd" class="fjt16qbnj"/><path clip-rule="evenodd" class="eee7vnjin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:three-d-glasses" /></template>
