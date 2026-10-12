<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pr317i25u.css';
import '../../css/l/lazq1ab7l.css';
import '../../css/e/em-eh2bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pr317i25u"/><path class="lazq1ab7l"/><path class="em-eh2bsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:messages-square-duotone" /></template>
