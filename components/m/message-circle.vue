<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmx_o5b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmx_o5b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle" /></template>
