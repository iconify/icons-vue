<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bos6iobsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bos6iobsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:settings-cog-plus-line" /></template>
