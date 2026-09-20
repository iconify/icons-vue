<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrjocabky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrjocabky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:megaphone-2" /></template>
