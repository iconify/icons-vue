<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry2_e2bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ry2_e2bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-code-filled" /></template>
