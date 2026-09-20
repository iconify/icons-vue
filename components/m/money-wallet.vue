<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r3q1v9_ye.css';
import '../../css/m/ml2e-ebew.css';
import '../../css/e/e_p8zmu7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r3q1v9_ye"/><path class="ml2e-ebew"/><path class="e_p8zmu7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:money-wallet" /></template>
