<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/omazkmbrf.css';
import '../../css/v/v1lgmvned.css';
import '../../css/m/myvq1cxds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="omazkmbrf"/><path class="v1lgmvned"/><path class="myvq1cxds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:vr-headset-2-flat" /></template>
