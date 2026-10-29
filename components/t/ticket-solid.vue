<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4bph3b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4bph3b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ticket-solid" /></template>
