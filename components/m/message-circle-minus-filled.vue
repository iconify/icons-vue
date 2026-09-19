<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf46e_bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf46e_bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-minus-filled" /></template>
