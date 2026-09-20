<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-agpl5uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r-agpl5uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:needle-and-spool-of-thread" /></template>
