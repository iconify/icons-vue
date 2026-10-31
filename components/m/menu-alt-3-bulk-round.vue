<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahowc3_6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahowc3_6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-alt-3-bulk-round" /></template>
