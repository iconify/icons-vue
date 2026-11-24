<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdi4l-b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdi4l-b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:zap-filled" /></template>
