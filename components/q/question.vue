<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ihd2q809h.css';
import '../../css/o/olg0x-m0f.css';
import '../../css/s/sovlp1b4o.css';
import '../../css/f/fv0al6bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ihd2q809h"/><path clip-rule="evenodd" class="olg0x-m0f"/><path clip-rule="evenodd" class="sovlp1b4o"/><path clip-rule="evenodd" class="fv0al6bdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:question" /></template>
