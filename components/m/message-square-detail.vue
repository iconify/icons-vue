<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmwufopie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmwufopie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-square-detail" /></template>
