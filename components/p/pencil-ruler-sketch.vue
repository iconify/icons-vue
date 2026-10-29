<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uivb_ubdk.css';
import '../../css/v/v55zsebyu.css';
import '../../css/q/q6z6ai9lv.css';
import '../../css/v/vkq-kzxjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uivb_ubdk"/><path class="v55zsebyu wm-a"/><path class="q6z6ai9lv wm-k"/><path class="vkq-kzxjk wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pencil-ruler-sketch" /></template>
