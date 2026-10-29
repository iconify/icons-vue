<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ayvoqcbmh.css';
import '../../css/k/k3e90fbez.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/s/samj1rluq.css';
import '../../css/k/k55be6yhw.css';
import '../../css/c/ck-4ht99s.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ayvoqcbmh wm-k"/><path class="k3e90fbez wm-a"/><path class="ol-kpp5cg wm-s"/><path class="samj1rluq wm-shadow"/><path class="k55be6yhw wm-k"/><path class="ck-4ht99s wm-a"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:timer-off-engrave" /></template>
