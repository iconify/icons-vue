<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q7d54sbwc.css';
import '../../css/k/k8xwvxi_d.css';
import '../../css/t/tgiuk7b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q7d54sbwc"/><path class="k8xwvxi_d"/><path class="tgiuk7b5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:merge-pdf-flat" /></template>
