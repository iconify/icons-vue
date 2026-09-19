<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lslr_dbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lslr_dbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-plus-filled" /></template>
