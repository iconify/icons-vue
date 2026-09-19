<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu7f6s55p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="iu7f6s55p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:netease-music-small" /></template>
