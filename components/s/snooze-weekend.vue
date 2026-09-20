<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp88opbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bp88opbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:snooze-weekend" /></template>
