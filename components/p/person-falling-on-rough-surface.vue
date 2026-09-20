<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfbhqh24h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gfbhqh24h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-falling-on-rough-surface" /></template>
