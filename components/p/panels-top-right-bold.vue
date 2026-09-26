<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gzdegqbrv.css';
import '../../css/q/qo3-r85um.css';
import '../../css/m/moaw0d06n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gzdegqbrv"/><path class="qo3-r85um"/><path clip-rule="evenodd" class="moaw0d06n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-top-right-bold" /></template>
