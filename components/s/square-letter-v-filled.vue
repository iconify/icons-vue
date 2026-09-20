<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctwjt065s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctwjt065s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-v-filled" /></template>
