<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm6di3box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="vm6di3box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waning-gibbous-3" /></template>
