<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm8mg3bjf.css';
import '../../css/o/o4nmjxj6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm8mg3bjf"/><path class="o4nmjxj6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:veur" /></template>
