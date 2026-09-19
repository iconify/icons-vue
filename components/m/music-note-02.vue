<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyc0af1ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyc0af1ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:music-note-02" /></template>
