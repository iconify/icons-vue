<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/ggfhrnbon.css';
import '../../css/q/qr3bw21xi.css';
import '../../css/t/ty2664dkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g transform="translate(2 5)" class="bi12bsetm"><path class="ggfhrnbon"/><circle class="qr3bw21xi"/><path class="ty2664dkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:stream-suite" /></template>
