<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nom3uiaev.css';
import '../../css/q/qphn1cb0k.css';
import '../../css/u/u0vpbrtxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nom3uiaev"/><path class="qphn1cb0k"/><path class="u0vpbrtxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shopping-bag-target" /></template>
