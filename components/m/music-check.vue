<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoou77l6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoou77l6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-check" /></template>
