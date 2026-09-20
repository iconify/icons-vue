<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i16-6_lek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i16-6_lek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:move-down-1" /></template>
