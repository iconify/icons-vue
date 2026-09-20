<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro-y-y6ov.css';
import '../../css/w/wavzocqjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro-y-y6ov"/><path class="wavzocqjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:moonrive" /></template>
