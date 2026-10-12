<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxqd53_2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxqd53_2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:play-filled" /></template>
