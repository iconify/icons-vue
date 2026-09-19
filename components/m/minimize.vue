<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg515_j0x.css';
import '../../css/g/go55dbb3w.css';
import '../../css/s/sr3x7wrjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="sg515_j0x"/><path class="go55dbb3w"/><path class="sr3x7wrjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:minimize" /></template>
