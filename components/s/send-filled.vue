<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0oq1yq9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0oq1yq9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:send-filled" /></template>
