<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf9l8pb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kf9l8pb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:question-small-outline" /></template>
