<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1arq4b0h.css';
import '../../css/w/wo_8mcpow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1arq4b0h"/><path class="wo_8mcpow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:phone-locked-filled" /></template>
