<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzi2wdfbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzi2wdfbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:plug-zap" /></template>
