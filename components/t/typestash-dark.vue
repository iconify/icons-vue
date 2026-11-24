<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1b0gzbhk.css';
import '../../css/l/lva836zoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s1b0gzbhk"/><path class="lva836zoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typestash-dark" /></template>
