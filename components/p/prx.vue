<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xarwckbam.css';
import '../../css/x/xakjq2afu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xarwckbam"/><path class="xakjq2afu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:prx" /></template>
