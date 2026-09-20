<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg18jvbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jg18jvbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:vim-normal-mode-16" /></template>
