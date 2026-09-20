<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kks44q3cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kks44q3cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:x-small-outline" /></template>
