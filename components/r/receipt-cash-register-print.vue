<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s--n7r_0v.css';
import '../../css/f/fes63hbvs.css';
import '../../css/n/nczupsdbg.css';
import '../../css/n/n5lgf897j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s--n7r_0v"/><path class="fes63hbvs"/><path class="nczupsdbg"/><path class="n5lgf897j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:receipt-cash-register-print" /></template>
