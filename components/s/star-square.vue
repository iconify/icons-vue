<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-wgyugil.css';
import '../../css/q/qlgozrxrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-wgyugil"/><path class="qlgozrxrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:star-square" /></template>
