<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xw8fpkimm.css';
import '../../css/b/bk8dcbcte.css';
import '../../css/s/svmnko8gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xw8fpkimm"/><path class="bk8dcbcte"/><path class="svmnko8gm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:webcam" /></template>
