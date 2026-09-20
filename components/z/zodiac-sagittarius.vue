<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx19rbc2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx19rbc2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:zodiac-sagittarius" /></template>
