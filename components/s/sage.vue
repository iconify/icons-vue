<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztmtb6bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztmtb6bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sage" /></template>
