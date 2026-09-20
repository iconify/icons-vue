<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am2benrmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am2benrmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:robot-industrial-outline" /></template>
