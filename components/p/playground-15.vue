<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7d_v9bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r7d_v9bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:playground-15" /></template>
