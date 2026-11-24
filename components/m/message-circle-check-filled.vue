<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r03x_bbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r03x_bbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-check-filled" /></template>
