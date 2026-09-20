<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klju58vbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="klju58vbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:smile" /></template>
