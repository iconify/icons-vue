<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0v6rsipu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i0v6rsipu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mybb" /></template>
