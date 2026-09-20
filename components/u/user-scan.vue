<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b680p_blz.css';
import '../../css/o/oq-b65kyl.css';
import '../../css/h/hipat9bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b680p_blz"/><path clip-rule="evenodd" class="oq-b65kyl"/><path class="hipat9bbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-scan" /></template>
