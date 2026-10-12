<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpptg2b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpptg2b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-dot-filled" /></template>
