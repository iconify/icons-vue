<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss_jp_aav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ss_jp_aav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:underline-text-1" /></template>
