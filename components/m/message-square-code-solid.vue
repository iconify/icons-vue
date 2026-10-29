<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi1fe2btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi1fe2btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-code-solid" /></template>
