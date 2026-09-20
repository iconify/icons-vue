<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/z4r1qykhw.css';
import '../../css/r/rn6sezfiu.css';
import '../../css/i/i6rghp2ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="z4r1qykhw"/><path class="rn6sezfiu"/><path class="i6rghp2ll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:money-bill-fly" /></template>
