<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp81v-bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jp81v-bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:upload-outline" /></template>
