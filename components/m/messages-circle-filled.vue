<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-p5e-beu.css';
import '../../css/o/oe8kfdbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-p5e-beu"/><path class="oe8kfdbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:messages-circle-filled" /></template>
