<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiwyrhbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fiwyrhbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:size-freeform-filled" /></template>
