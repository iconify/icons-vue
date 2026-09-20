<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajifrufrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajifrufrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sim-card-2-filled" /></template>
