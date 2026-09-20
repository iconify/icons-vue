<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8vknfx4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b8vknfx4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vert-light" /></template>
