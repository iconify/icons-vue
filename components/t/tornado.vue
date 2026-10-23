<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzn940boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzn940boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:tornado" /></template>
