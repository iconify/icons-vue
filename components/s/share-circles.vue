<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/oys3jfy5i.css';
import '../../css/h/h1w9cac_o.css';
import '../../css/k/klv_anb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="oys3jfy5i"/><path class="h1w9cac_o"/><path class="klv_anb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:share-circles" /></template>
