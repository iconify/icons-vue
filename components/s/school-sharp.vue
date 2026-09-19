<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0m-rizhq.css';
import '../../css/z/z0wxf4bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p0m-rizhq"/><path class="z0wxf4bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:school-sharp" /></template>
