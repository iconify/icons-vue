<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5-mp9b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="i5-mp9b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:meh-o" /></template>
