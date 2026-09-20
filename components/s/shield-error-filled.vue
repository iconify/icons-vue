<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8l4_q72h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8l4_q72h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:shield-error-filled" /></template>
