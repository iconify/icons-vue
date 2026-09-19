<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_9m_3b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g_9m_3b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shopping-bag-outline" /></template>
