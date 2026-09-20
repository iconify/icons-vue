<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heqfjacds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="heqfjacds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:vim-command-mode-16" /></template>
