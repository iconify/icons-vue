<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg71s5b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bg71s5b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:u" /></template>
