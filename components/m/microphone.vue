<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwzbg8b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bwzbg8b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:microphone" /></template>
