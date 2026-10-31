<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hieyli1np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hieyli1np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-size-decrease-duotone-round" /></template>
