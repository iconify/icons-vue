<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/p5tqq5pwc.css';
import '../../css/u/ukvmc8bfw.css';
import '../../css/g/g0k5_ba-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="p5tqq5pwc"/><circle class="ukvmc8bfw"/><path class="g0k5_ba-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:speaker" /></template>
