<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3m_32d1b.css';
import '../../css/m/mvqkmbccf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3m_32d1b"/><path class="mvqkmbccf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:question-circle" /></template>
