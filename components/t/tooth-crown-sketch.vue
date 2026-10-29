<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ae0h0ywtu.css';
import '../../css/k/k7nygkzdg.css';
import '../../css/a/ayydkbl3e.css';
import '../../css/m/mqno2ebsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ae0h0ywtu"/><path class="k7nygkzdg wm-a"/><path class="ayydkbl3e wm-k"/><path class="mqno2ebsq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tooth-crown-sketch" /></template>
