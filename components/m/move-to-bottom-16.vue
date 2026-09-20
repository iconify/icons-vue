<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9xce2utg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s9xce2utg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:move-to-bottom-16" /></template>
