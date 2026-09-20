<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya-g8j0vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya-g8j0vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:player-pause" /></template>
