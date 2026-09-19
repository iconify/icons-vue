<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jky9q57sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jky9q57sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:plus" /></template>
