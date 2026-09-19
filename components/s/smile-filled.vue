<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki_ssibof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki_ssibof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:smile-filled" /></template>
