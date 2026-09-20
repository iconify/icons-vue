<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt0usqk2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kt0usqk2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tag-alt-solid" /></template>
