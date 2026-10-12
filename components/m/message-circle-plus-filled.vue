<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu_3dgbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xu_3dgbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-plus-filled" /></template>
