<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh-ohcc2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh-ohcc2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:safe" /></template>
