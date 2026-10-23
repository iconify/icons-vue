<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tav14-bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tav14-bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:voicemail" /></template>
