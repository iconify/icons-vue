<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dnimzpbzq.css';
import '../../css/o/o1-lycc9y.css';
import '../../css/v/v2tabnved.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dnimzpbzq"/><path class="o1-lycc9y"/><path class="v2tabnved"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ruler-duotone" /></template>
