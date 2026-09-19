<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uamsnbbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uamsnbbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:undo" /></template>
