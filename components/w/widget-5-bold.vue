<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yspjl-b4f.css';
import '../../css/o/ozjn960ga.css';
import '../../css/m/mucmghbzo.css';
import '../../css/z/zi-y_bbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yspjl-b4f"/><path class="ozjn960ga"/><path class="mucmghbzo"/><path class="zi-y_bbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-5-bold" /></template>
