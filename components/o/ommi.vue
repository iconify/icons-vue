<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjo-1vbvf.css';
import '../../css/l/l-88s82ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjo-1vbvf"/><path class="l-88s82ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ommi" /></template>
