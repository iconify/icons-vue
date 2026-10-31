<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjk_vvbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjk_vvbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-help-round" /></template>
