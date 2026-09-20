<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm0bdzbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm0bdzbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rdpx" /></template>
