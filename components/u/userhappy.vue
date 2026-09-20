<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnn7-0g9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xnn7-0g9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:userhappy" /></template>
