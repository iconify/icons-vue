<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gip4t6bed.css';
import '../../css/g/gdhs6pexy.css';
import '../../css/n/nrxmdfbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gip4t6bed"/><path class="gdhs6pexy"/><path class="nrxmdfbsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:water-fountain-drink" /></template>
