<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_d0yw8xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m_d0yw8xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:vim-select-mode-16" /></template>
