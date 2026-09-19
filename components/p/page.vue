<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw-pbdcck.css';
import '../../css/u/ucdp9ybuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pw-pbdcck"/><path class="ucdp9ybuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:page" /></template>
