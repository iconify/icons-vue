<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jw-0m_b3v.css';
import '../../css/k/kmzc8gbuh.css';
import '../../css/g/gmdfz2brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="jw-0m_b3v"/><path class="kmzc8gbuh"/><path class="gmdfz2brc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:worm" /></template>
