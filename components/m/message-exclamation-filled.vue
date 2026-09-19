<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnuq4e15h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnuq4e15h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-exclamation-filled" /></template>
