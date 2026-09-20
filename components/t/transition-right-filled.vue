<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8x6g5o0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8x6g5o0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transition-right-filled" /></template>
