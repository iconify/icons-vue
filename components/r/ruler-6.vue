<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/a/ay9ax4btl.css';
import '../../css/y/yjilmu12q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="ay9ax4btl"/><path class="yjilmu12q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:ruler-6" /></template>
