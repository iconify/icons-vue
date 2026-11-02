<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk-f31lyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk-f31lyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rare-fog-lights-fill" /></template>
