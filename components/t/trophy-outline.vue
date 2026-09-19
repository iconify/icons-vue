<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhb5h3agu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rhb5h3agu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:trophy-outline" /></template>
