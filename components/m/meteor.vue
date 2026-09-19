<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu1nxz26a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="eu1nxz26a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:meteor" /></template>
