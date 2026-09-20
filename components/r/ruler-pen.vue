<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed8wa8zsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ed8wa8zsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ruler-pen" /></template>
