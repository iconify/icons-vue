<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh2ov0byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fh2ov0byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:montana-with-capital-star" /></template>
