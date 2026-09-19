<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/garwd4hif.css';
import '../../css/d/d0gmrybii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="garwd4hif"/><path class="d0gmrybii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:restructuredtext" /></template>
