<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzwtx_bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzwtx_bod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wenxin" /></template>
