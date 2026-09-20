<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_4h3zllq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="m_4h3zllq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:pitch-11" /></template>
