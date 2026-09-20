<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/x/xxswp1bkt.css';
import '../../css/h/h8y-n3_nj.css';
import '../../css/g/gn_7n3t9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xxswp1bkt"/><path class="h8y-n3_nj"/><path class="gn_7n3t9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shop-remove" /></template>
