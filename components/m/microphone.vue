<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofmw9kbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofmw9kbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:microphone" /></template>
