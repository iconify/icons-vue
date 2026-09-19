<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7cxk4byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s7cxk4byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:workspace-untrusted" /></template>
