<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox_hucdtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_hucdtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moai-line" /></template>
