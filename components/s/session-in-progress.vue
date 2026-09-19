<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/triztubxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="triztubxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:session-in-progress" /></template>
