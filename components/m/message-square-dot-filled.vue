<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud9cl0y3d.css';
import '../../css/a/aba_xubdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud9cl0y3d"/><path class="aba_xubdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-square-dot-filled" /></template>
