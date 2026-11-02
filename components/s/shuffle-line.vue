<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8px5wr7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8px5wr7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shuffle-line" /></template>
