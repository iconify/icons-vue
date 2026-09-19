<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q97m5m7xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q97m5m7xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:speaker-mute" /></template>
