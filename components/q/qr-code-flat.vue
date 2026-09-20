<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/krcelihbz.css';
import '../../css/n/n76sdzv2k.css';
import '../../css/q/q44e-r43q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="krcelihbz"/><path class="n76sdzv2k"/><path class="q44e-r43q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:qr-code-flat" /></template>
