<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byywln2tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="byywln2tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-picasa" /></template>
