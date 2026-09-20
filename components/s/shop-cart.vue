<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n2neiybmu.css';
import '../../css/h/he2cb6v8q.css';
import '../../css/q/qhj_kmfui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n2neiybmu"/><path class="he2cb6v8q"/><path class="qhj_kmfui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shop-cart" /></template>
