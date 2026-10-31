<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4qvdaclo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4qvdaclo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-size-decrease-fill-round" /></template>
