<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upt-3cclz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upt-3cclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-image-filled" /></template>
