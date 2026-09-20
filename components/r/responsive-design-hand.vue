<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g7kk0pbfc.css';
import '../../css/s/s43gu1b2k.css';
import '../../css/k/kq3qq5bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="g7kk0pbfc"/><path class="s43gu1b2k"/><path class="kq3qq5bpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:responsive-design-hand" /></template>
