<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr1ca3b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr1ca3b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:stack-2-filled" /></template>
