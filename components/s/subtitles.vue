<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhl3a5t6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhl3a5t6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:subtitles" /></template>
