<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/o2dydi33t.css';
import '../../css/t/t-u0yzblp.css';
import '../../css/g/gcoh1u6ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o2dydi33t"/><circle class="t-u0yzblp"/><path class="gcoh1u6ei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:user-minus" /></template>
