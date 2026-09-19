<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnyqblbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnyqblbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:penis-alt-outline-24px" /></template>
