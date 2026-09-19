<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-grg3b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="a-grg3b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:mars-stroke" /></template>
