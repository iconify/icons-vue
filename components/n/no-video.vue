<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-dd5ubvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-dd5ubvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-video" /></template>
