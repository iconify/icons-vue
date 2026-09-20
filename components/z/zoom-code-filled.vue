<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv-60l-dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv-60l-dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-code-filled" /></template>
