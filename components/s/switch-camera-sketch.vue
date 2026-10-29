<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zkrfzvbns.css';
import '../../css/l/l24jhwj-r.css';
import '../../css/f/fluce_b-m.css';
import '../../css/b/b1j359zmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zkrfzvbns"/><path class="l24jhwj-r wm-a"/><path class="fluce_b-m wm-k"/><path class="b1j359zmm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:switch-camera-sketch" /></template>
