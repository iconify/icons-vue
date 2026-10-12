<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v1euu_nkh.css';
import '../../css/s/s930m50lb.css';
import '../../css/g/gq_3b3b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v1euu_nkh"/><path class="s930m50lb"/><path class="gq_3b3b8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mic-duotone" /></template>
