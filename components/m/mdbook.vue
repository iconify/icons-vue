<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9c9wr01r.css';
import '../../css/r/rdsfeeb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g9c9wr01r"/><path class="rdsfeeb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:mdbook" /></template>
