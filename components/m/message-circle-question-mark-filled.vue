<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8t8hmbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l8t8hmbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-question-mark-filled" /></template>
