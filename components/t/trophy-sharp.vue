<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft4kbctzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft4kbctzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:trophy-sharp" /></template>
