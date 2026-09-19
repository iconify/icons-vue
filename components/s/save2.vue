<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9rwoxb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s9rwoxb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:save2" /></template>
