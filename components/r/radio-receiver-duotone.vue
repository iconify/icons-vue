<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i6uzpybyf.css';
import '../../css/p/phm_mqkqd.css';
import '../../css/w/w6pvigl7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i6uzpybyf"/><path class="phm_mqkqd"/><path class="w6pvigl7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:radio-receiver-duotone" /></template>
