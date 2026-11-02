<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-53rmblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-53rmblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-x-fill" /></template>
