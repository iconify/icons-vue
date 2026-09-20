<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t6a4tpbqc.css';
import '../../css/i/ij7j57b7c.css';
import '../../css/x/xsjxoiu5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="t6a4tpbqc"/><path class="ij7j57b7c"/><path class="xsjxoiu5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:polaroid-flat" /></template>
