<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8qss41br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8qss41br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:subtitles-off" /></template>
