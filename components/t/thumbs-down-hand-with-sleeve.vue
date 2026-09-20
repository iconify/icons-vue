<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt--_cb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kt--_cb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:thumbs-down-hand-with-sleeve" /></template>
