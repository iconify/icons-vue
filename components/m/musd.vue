<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj_u7vbcr.css';
import '../../css/x/xgapgabzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj_u7vbcr"/><path class="xgapgabzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:musd" /></template>
