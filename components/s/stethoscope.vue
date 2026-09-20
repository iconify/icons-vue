<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9eax3b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9eax3b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:stethoscope" /></template>
