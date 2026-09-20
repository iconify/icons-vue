<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/ca13g7t3o.css';
import '../../css/h/h78girq9f.css';
import '../../css/u/u54lry2-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ca13g7t3o"/><path class="h78girq9f"/><path class="u54lry2-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:strategy-business-success-peak" /></template>
