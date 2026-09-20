<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4slog9tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4slog9tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:metro-variant" /></template>
