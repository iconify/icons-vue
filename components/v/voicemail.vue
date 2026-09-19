<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tosz15bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tosz15bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:voicemail" /></template>
