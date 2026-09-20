<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ths0tvdky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ths0tvdky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-2-bold" /></template>
