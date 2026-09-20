<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/ptpca_ffg.css';
import '../../css/m/m9ted4zaz.css';
import '../../css/w/wdkf5qwjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ptpca_ffg"/><path class="m9ted4zaz"/><circle class="wdkf5qwjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:search-duotone" /></template>
