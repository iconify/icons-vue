<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llqk24png.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="llqk24png"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unmute-16" /></template>
