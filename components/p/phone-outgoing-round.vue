<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql759x68e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql759x68e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-outgoing-round" /></template>
