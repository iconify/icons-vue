<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq-kzfbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tq-kzfbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:pinned-dirty" /></template>
