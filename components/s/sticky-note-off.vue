<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qij98ubos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qij98ubos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sticky-note-off" /></template>
