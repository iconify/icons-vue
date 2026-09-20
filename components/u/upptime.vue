<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nde_ibbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nde_ibbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:upptime" /></template>
