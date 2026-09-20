<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1mjul3vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n1mjul3vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:vim-replace-mode-16" /></template>
