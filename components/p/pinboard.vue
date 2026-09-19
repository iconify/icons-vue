<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w494h98hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="w494h98hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:pinboard" /></template>
