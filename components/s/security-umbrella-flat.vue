<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p4hsu1cam.css';
import '../../css/n/nf6h_omja.css';
import '../../css/n/ncufwjbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="p4hsu1cam"/><path class="nf6h_omja"/><path class="ncufwjbwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:security-umbrella-flat" /></template>
