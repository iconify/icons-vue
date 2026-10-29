<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ir-rmujqd.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/g/g3cuk7bic.css';
import '../../css/v/vxuqhab0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ir-rmujqd"/><path class="qr4ochb5c wm-s"/><path class="g3cuk7bic"/><path class="vxuqhab0r wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:monitor-off-duo" /></template>
