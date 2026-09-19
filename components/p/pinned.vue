<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/got3ckffi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="got3ckffi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:pinned" /></template>
