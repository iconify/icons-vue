<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cegur4clo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cegur4clo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:microphone-2" /></template>
