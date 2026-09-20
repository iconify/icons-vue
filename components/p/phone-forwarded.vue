<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xey14xbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xey14xbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:phone-forwarded" /></template>
