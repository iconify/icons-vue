<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx3vb3kpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx3vb3kpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:scan-letter-t" /></template>
