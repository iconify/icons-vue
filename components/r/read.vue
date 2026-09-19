<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se8m_e3yt.css';
import '../../css/h/hp28okb8j.css';
import '../../css/z/z040k9bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se8m_e3yt"/><path class="hp28okb8j"/><circle class="z040k9bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:read" /></template>
