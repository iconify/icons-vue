<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1s5h0bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1s5h0bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plane-departure-filled" /></template>
