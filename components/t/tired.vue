<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmu3bk6pi.css';
import '../../css/w/wqbkv8u2i.css';
import '../../css/k/k31e-btyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmu3bk6pi"/><path class="wqbkv8u2i"/><path class="k31e-btyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:tired" /></template>
