<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx1ngfbkm.css';
import '../../css/n/n6y0s7eue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx1ngfbkm"/><path class="n6y0s7eue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:palace-3-filled" /></template>
