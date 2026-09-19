<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqhf__4kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="kqhf__4kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:treeornament" /></template>
