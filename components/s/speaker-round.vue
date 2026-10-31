<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csux-tsoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csux-tsoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:speaker-round" /></template>
