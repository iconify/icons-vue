<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh82h5geo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xh82h5geo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:subtitles-fill" /></template>
