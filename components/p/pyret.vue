<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt7r-bbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":500};
const content = `<path class="kt7r-bbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pyret" /></template>
