<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfj-wcb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cfj-wcb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:microphone-off-solid" /></template>
