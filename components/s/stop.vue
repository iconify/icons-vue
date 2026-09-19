<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr42-txod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rr42-txod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:stop" /></template>
