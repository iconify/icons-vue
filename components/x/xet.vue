<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhle38bke.css';
import '../../css/f/fsl5_2myu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhle38bke"/><path class="fsl5_2myu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xet" /></template>
