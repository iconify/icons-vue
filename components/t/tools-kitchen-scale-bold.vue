<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8okp_dga.css';
import '../../css/o/o5ofv024l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8okp_dga"/><path class="o5ofv024l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:tools-kitchen-scale-bold" /></template>
