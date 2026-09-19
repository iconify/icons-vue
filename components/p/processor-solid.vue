<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkkv6qbnz.css';
import '../../css/m/mg4u22kbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkkv6qbnz"/><path clip-rule="evenodd" class="mg4u22kbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:processor-solid" /></template>
