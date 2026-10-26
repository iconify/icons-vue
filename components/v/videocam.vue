<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlmx0q-5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rlmx0q-5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:videocam" /></template>
