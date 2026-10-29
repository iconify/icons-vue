<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf81lhb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf81lhb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:zap-off" /></template>
