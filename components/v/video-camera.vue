<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lym7mzbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lym7mzbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:video-camera" /></template>
