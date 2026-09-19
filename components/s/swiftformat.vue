<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu96i2m6r.css';
import '../../css/f/fbfcujy1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pu96i2m6r"/><path class="fbfcujy1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:swiftformat" /></template>
