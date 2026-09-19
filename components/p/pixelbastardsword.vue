<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c25m_hbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c25m_hbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixelbastardsword" /></template>
