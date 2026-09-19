<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s49v1cqka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s49v1cqka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:test-js" /></template>
