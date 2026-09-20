<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp1y_acrv.css';
import '../../css/x/xm9k567sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp1y_acrv"/><path class="xm9k567sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:shx" /></template>
