<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wigpk_r0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wigpk_r0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-text-solid" /></template>
