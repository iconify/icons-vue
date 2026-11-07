<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-z4ujbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-z4ujbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-rounded-2-linear" /></template>
