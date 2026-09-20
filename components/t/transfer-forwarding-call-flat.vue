<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bvsh4tcni.css';
import '../../css/l/l9_nzpkbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bvsh4tcni"/><path class="l9_nzpkbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:transfer-forwarding-call-flat" /></template>
