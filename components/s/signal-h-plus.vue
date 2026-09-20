<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rot91g7vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rot91g7vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:signal-h-plus" /></template>
