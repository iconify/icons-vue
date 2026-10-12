<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5i5m5e2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y5i5m5e2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-square-code-filled" /></template>
