<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccucf8nmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccucf8nmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pin-slash-alt" /></template>
