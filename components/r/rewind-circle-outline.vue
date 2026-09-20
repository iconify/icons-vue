<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9ytizxvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q9ytizxvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rewind-circle-outline" /></template>
