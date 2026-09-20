<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bao23p41t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bao23p41t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-lock-fill" /></template>
