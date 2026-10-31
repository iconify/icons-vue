<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smr7-1bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smr7-1bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-1-round" /></template>
