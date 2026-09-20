<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkkgjcceq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkkgjcceq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speaker-2-fill" /></template>
