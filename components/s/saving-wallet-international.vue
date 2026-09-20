<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m_s4vf09q.css';
import '../../css/x/xust17bnz.css';
import '../../css/s/sphoe-x3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m_s4vf09q"/><path class="xust17bnz"/><path class="sphoe-x3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:saving-wallet-international" /></template>
