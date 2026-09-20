<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwe2b1h6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iwe2b1h6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:playlist-16" /></template>
