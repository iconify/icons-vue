<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr4c9lt1j.css';
import '../../css/l/lp5zebcnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="rr4c9lt1j"/><path class="lp5zebcnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:message-alt-duotone-line" /></template>
