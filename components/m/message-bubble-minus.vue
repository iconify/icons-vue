<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqirleobg.css';
import '../../css/a/aevd0o1gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqirleobg"/><path class="aevd0o1gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-minus" /></template>
