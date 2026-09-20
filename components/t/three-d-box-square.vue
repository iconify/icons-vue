<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/f/fj8mgub1r.css';
import '../../css/y/y-i__ff-j.css';
import '../../css/z/z7h9dmbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="fj8mgub1r"/><path class="y-i__ff-j"/><rect class="z7h9dmbpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:three-d-box-square" /></template>
