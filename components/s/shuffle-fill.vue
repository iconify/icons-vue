<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wba5tcc0y.css';
import '../../css/n/nm-b5odlu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wba5tcc0y"/><path class="nm-b5odlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:shuffle-fill" /></template>
