<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taydzab8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="taydzab8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:yen-circle" /></template>
