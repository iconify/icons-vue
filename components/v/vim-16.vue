<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdk21pi7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bdk21pi7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:vim-16" /></template>
