<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xipc_jbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xipc_jbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-high-round" /></template>
