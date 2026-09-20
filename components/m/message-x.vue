<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd82nybwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd82nybwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-x" /></template>
