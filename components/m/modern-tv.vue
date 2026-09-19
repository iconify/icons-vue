<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9c6y2b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9c6y2b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:modern-tv" /></template>
